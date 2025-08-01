# Task_05_Descriptive_Stats

## Reflections on LLM Evaluation

Working with LLMs (ChatGPT-4) on this dataset (2025) was insightful. The models were highly accurate when answering direct, fact-based questions based on provided summaries or basic stats. For example, they correctly computed save percentages, shot conversion rates, and trends in period-wise performance.

However, limitations emerged when the questions required player-level data or inferred insights not explicitly available. For instance, when asked to identify the "most improved player," the LLM fabricated an answer by assuming a pattern based on aggregate stats. This reflects a common risk with LLMs: confident-sounding hallucinations in the absence of structured context.

What worked well:
- Summarized stat prompts and clear formatting improved accuracy.
- Models excelled at basic math and trend identification.

What didn’t work:
- Lack of granularity (e.g., player-level data) led to unsupported assumptions.
- Some models failed to acknowledge “unknown” when data was insufficient.

Overall, LLMs are powerful for interpreting and summarizing structured sports data, but care must be taken in prompt design and answer validation.
