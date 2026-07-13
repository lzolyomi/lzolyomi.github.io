---
layout: page
title: TiRex
description: xLSTM-based time series foundation model
img: assets/img/12.jpg
importance: 1
category: research
related_publications: false
---

TiRex is an xLSTM-based time series foundation model developed at NXAI. It leverages the linear recurrence and gated memory mechanisms of xLSTM for efficient zero-shot forecasting on diverse time series datasets.

**TiRex-2** (arXiv:2607.01204, July 2026) extends TiRex to multivariate forecasting with both past and future covariates. It introduces a memory-centric recurrent design with constant per-patch cost under streaming, a bidirectional time mixer with asymmetric grouped-attention variate mixer, and a synthetic coupling pipeline for scalable multivariate pretraining. TiRex-2 achieves state-of-the-art zero-shot performance on GIFT-Eval and fev-bench.
