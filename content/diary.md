---
title: Listening Diary
date: "2026-06-14T00:00:00Z"
draft: false
share: false
commentable: false
editable: false

header:
  caption: ""
  image: ""
---

**Listening Diary** is a system that logs every song the user plays and scores the
**mood of the audio itself** with a neural audio model (CLAP). A parallel channel
scores the **mood of the lyrics** (multilingual text embeddings), so the diary can
surface the most interesting signal of all: when a song **sounds** one way but
**reads** another ("sounds happy · reads sad"). It can be run entirely on a local
machine.

The diary below is a single self-contained, interactive HTML view — a month
**heatmap** of daily mood, a two-lane **timeline** putting audio next to lyrics,
and **divergence tags** where the two disagree.

> **Note:** this is a **demo populated with synthetic data** — invented songs and
> artists, not real listening history.

<div style="margin: 1.5rem 0;">
  <iframe src="/diary-demo.html"
          title="Listening Diary demo"
          loading="lazy"
          style="width:100%; height:640px; border:1px solid #ddd; border-radius:8px;">
  </iframe>
</div>

<p style="font-size:1.05rem;">
  👉 <strong><a href="/diary-demo.html" target="_blank" rel="noopener">Open the full interactive demo →</a></strong>
  &nbsp;(best experience — hover for per-song mood charts, click a busy evening to
  expand it; these float past the preview box above).
</p>

### Interested to know more?

Get in touch:
[email](mailto:amirmohammadkz@gmail.com) ·
[LinkedIn](https://www.linkedin.com/in/amirmohammadkz).
