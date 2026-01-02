TrustLens

Evaluation-First Claim-Level AI Reliability System

TrustLens is a production-oriented, evaluation-first system for identifying factual risk in AI-generated text at the claim level. Rather than judging entire responses as correct or incorrect, TrustLens decomposes text into individual claims, verifies each against evidence, and surfaces calibrated risk signals with clear decision thresholds and human-in-the-loop feedback.

The project emphasizes model evaluation, calibration, and system behavior under uncertainty, not just raw model accuracy.

Problem Motivation

Modern LLM outputs are often fluent and mostly correct, but may contain localized hallucinations—single fabricated facts embedded within otherwise accurate text. These errors are difficult to detect without claim-level inspection and pose real risk in high-stakes domains.

TrustLens addresses this by:

Treating claims as the unit of analysis

Surfacing probabilistic risk signals, not binary judgments

Prioritizing recall for high-risk claims

Making evaluation metrics drive product behavior

Core Principles

Evaluation-first design: metrics, thresholds, and calibration are first-class system components

Recall > precision for high-risk claims

Explicit uncertainty: model outputs are treated as probabilistic signals

Human-in-the-loop: feedback is captured as an evaluation signal, not ground truth

Transparency: users can inspect evidence and model reasoning per claim