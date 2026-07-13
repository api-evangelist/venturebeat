---
title: "Google's TabFM skips per-dataset training and still predicts on tables it's never seen"
url: "https://venturebeat.com/technology/googles-tabfm-skips-per-dataset-training-and-still-predicts-on-tables-its-never-seen"
date: "2026-07-10"
author: "bendee983@gmail.com (Ben Dickson)"
feed_url: "https://venturebeat.com/feed"
---
The vast majority of business data is tabular — living in data warehouses, CRMs, and financial ledgers — yet building a reliable model from it still means training a new one from scratch for every dataset, then maintaining hyperparameter tuning loops, feature engineering, and retraining pipelines to fight data drift. Google Research is proposing a way around that: a new foundation model called TabFM that treats tabular prediction as an in-context learning problem instead. It can generate predictions for a new, unseen table in a single forward pass.
