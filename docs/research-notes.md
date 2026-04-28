# tmux for OpenCUA: Robustness Evaluation

## Purpose

This document records the research framing behind the static GitHub Pages site. The project studies how tmux can be adapted for OpenCUA as a durable terminal substrate for agentic work.

## Research Question

When OpenCUA moves between local, remote, and instrumented terminal environments, what forms of tmux state remain reliable?

## Working Thesis

Robustness is best studied as a portability problem: the same task trace should remain interpretable after shell differences, resize events, and remote latency.

## Design Claims

- Environment profiles capture shell, terminal size, locale, and remote transport.
- Trace replay highlights where observation normalization fails.
- Evaluation distinguishes transport errors from agent decision errors.

## Evaluation Lens

- Cross-shell replay fidelity
- Latency sensitivity of command feedback
- Failure attribution quality


## Threats to Validity

- Terminal state can be over-instrumented, causing an adapter to measure artifacts of the harness rather than real agent behavior.
- A final successful artifact may hide poor recovery behavior, repeated command attempts, or fragile focus management.
- Agent-specific adapters can become difficult to compare unless trace schemas remain explicit and documented.

## Hero Image Prompt Summary

A 700x500 academic technical illustration for tmux adaptation research with OpenCUA, emphasizing terminal panes, agent traces, reproducible evaluation, and a serious research discussion style. The generated image was copied into `docs/assets/hero.png` and normalized to 700x500 pixels.
