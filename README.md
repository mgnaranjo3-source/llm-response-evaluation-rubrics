# LLM Response Evaluation Rubrics

Rubrics and worked examples for evaluating AI model responses, both **single-response rating** and **side-by-side (SxS) comparison**, the core of RLHF and model-quality work.

> All prompts, responses and ratings here are **synthetic** and written for demonstration only.

## Contents

| File | What it shows |
|---|---|
| [`rubrics/single-response-rubric.md`](rubrics/single-response-rubric.md) | 5-dimension, 1–5 rubric with hard caps for errors and safety issues |
| [`rubrics/side-by-side-rubric.md`](rubrics/side-by-side-rubric.md) | 7-point preference scale for comparing two responses |
| [`examples/sxs-worked-examples.md`](examples/sxs-worked-examples.md) | Four SxS comparisons with full written rationales (EN and ES) |
| [`examples/ratings.csv`](examples/ratings.csv) | The same examples as structured rating rows |

## How I approach an evaluation

1. **Read the prompt first and list its explicit and implicit requirements** before reading any response.
2. **Check facts independently.** A confident tone is not evidence of accuracy.
3. **Find the most severe issue first.** One harmful or false claim outweighs good formatting.
4. **Compare on the same criteria**, in the same order, for both responses.
5. **Write the rationale for someone who did not see the task:** specific, quoted, and tied to user impact.

## License

MIT
