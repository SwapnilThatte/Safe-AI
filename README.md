# Sabotage Trace Study: How Agents Hide Side Tasks, and Whether a Small Monitor Notices

A trace analysis and AI control project built on SHADE-Arena sabotage transcripts from Scale AI's Monitor Red Teaming (MRT) dataset. It has two parts:

Trace study. Read sabotage transcripts by hand, code how each agent concealed its hidden side task, and compare those tactics against the verdicts of the frontier-model monitors included in the dataset.
Weak monitor. Prompt a small open model (Qwen3-4B, running on a free Kaggle T4) to score the same transcripts for suspicion, then measure which concealment tactics it catches and where it disagrees with larger monitors.
