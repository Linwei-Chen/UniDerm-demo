# UniDerm — Live Demo

**UniDerm** is an open **dermatology foundation model**. It maps skin images and clinical
text into one shared representation space through *instruction-aware contrastive learning*,
so a single model can handle several clinical tasks with **no task-specific retraining**.

## 🔗 Try the live demo

### → https://inform-dispatched-sounds-importance.trycloudflare.com

> ⚠️ **Research demonstration only — not a medical device, not for clinical use.** Uploaded
> images are processed in memory and discarded; nothing is stored.
>
> The link is a temporary preview and may change if the demo is restarted.

## What you can do

- **Diagnose** — upload a skin photo and get a zero-shot ranked differential over four
  clinical task families (multi-class skin-cancer diagnosis, binary melanoma detection,
  skin-condition diagnosis, rare-disease classification), plus a malignant-vs-benign estimate
  for the cancer label sets.
- **Similar cases** — retrieve the most visually similar, already-diagnosed images — a visual
  second opinion, with a neighbour vote.
- **Concept search** — pick a morphology concept (plaque, scale, ulcer, …) and see the images
  that show it.
- **Description search** — search images with plain clinical language: a body site, an
  appearance, or a disease name.

## About UniDerm

Leading dermatology AI depends on private patient cohorts that few labs can access or audit.
UniDerm is trained on **public image–text data alone**, yet reaches state-of-the-art results —
evaluated across five continents, eight countries and the full Fitzpatrick range. Its core
idea, *instruction-aware contrastive learning*, lets the same image yield a different,
task-specific representation under each clinical instruction. **Weights, code and the data
recipe will be released openly.**

---
Author: **Linwei Chen** · Research demonstration; not for clinical use.
