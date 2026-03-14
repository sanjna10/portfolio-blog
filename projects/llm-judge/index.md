---
layout: project
title: LLM-as-a-Judge for Cybersecurity
subtitle: Studying rubric-based evaluation pipelines for cybersecurity benchmarks, focusing on consistency, reasoning quality, and faithfulness.
permalink: /projects/llm-judge/
---

## Introduction and Motivation

This project explores whether LLM-based judges can reliably evaluate answers in cybersecurity settings. The focus is on building an evaluation framework that goes beyond exact-match metrics and also checks reasoning quality, rubric alignment, and hallucination behavior.

## Background

Recent work in LLM-as-a-Judge shows promise for scalable evaluation, but reliability depends heavily on rubric design, prompting, and benchmark structure. Cybersecurity is especially challenging because answers often require precision, domain grounding, and safe reasoning.

## Approach

The project investigates:
- rubric-based scoring
- exact-match versus judge-based scoring
- pairwise and pointwise evaluation settings
- consistency across prompts and models

## Datasets and Evaluation

We evaluate on cybersecurity-style benchmark tasks with structured prompts, reference answers, and scoring criteria.

## Results and Takeaways

The project aims to identify where LLM judges are useful, where they fail, and what design choices improve trustworthiness in evaluation.