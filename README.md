A.U.R.O.R.A.
Multimodal Digital Forensics & Synthetic Content Analysis

Some systems are built to create.

Some are built to understand.

A.U.R.O.R.A. was built to determine what happened.

The A.U.R.O.R.A. Project

There was a project called A.U.R.O.R.A.

It was designed with an ambitious objective:

To understand the origin of digital information by analyzing the traces left behind during its creation, transformation and manipulation.

The original project never became what it was intended to become.

The technology was incomplete.
The infrastructure was insufficient.
The problem itself was larger than initially understood.

But the idea remained.

Years later, A.U.R.O.R.A. is being rebuilt from the ground up.

Not as a system that blindly declares whether something was created by an AI.

Not as a black-box classifier.

And not as a machine that claims to know the unknowable.

Instead, the new A.U.R.O.R.A. is being designed around a simpler principle:

Digital content leaves evidence.

Text leaves linguistic patterns.

Images leave statistical and forensic traces.

Audio leaves spectral characteristics.

Video leaves temporal inconsistencies.

Code leaves structural and stylistic patterns.

Files leave metadata, hashes and structural information.

And sometimes, digital content carries something even more valuable:

verifiable provenance.

A.U.R.O.R.A. exists to collect these signals, evaluate them independently and combine them into a transparent probabilistic assessment.

What is A.U.R.O.R.A.?

A.U.R.O.R.A. is an experimental multimodal digital forensics and synthetic-content analysis system.

Its objective is to estimate whether digital content is consistent with:

primarily human creation;
AI-assisted human creation;
primarily synthetic generation;
AI-generated content subsequently modified by humans;
AI-based manipulation;
or an indeterminate origin.

The system is explicitly not designed to provide absolute attribution.

Instead, it produces an evidence-based assessment containing:

Estimated probability
Confidence
Detected signals
Models used
Supporting evidence
Contradicting evidence
Provenance information
Known limitations

The fundamental question is therefore not:

"Was this made by AI?"

but:

"What evidence does the available data provide about how this content may have been created or modified?"

Core Philosophy

A.U.R.O.R.A. follows five principles.

1. Detection is not proof

A statistical detector can indicate that content resembles material produced by generative systems.

It cannot automatically prove who created it.

2. Provenance is different from detection

Detecting synthetic-looking characteristics and proving the origin of an artifact are different problems.

A.U.R.O.R.A. therefore separates:

Synthetic-content analysis
            │
            ├── statistical evidence
            ├── ML predictions
            └── forensic signals

                    ≠

Digital provenance
            │
            ├── metadata
            ├── hashes
            ├── signatures
            ├── Content Credentials
            └── C2PA information
3. Multiple signals are better than a single detector

No individual signal should automatically determine the final assessment.

The architecture therefore favors:

Signal A ─┐
Signal B ─┤
Signal C ─┤
Signal D ─┤
Metadata ─┤
Provenance┘
     │
     ▼
Evidence Fusion
     │
     ▼
Probabilistic Assessment
4. Uncertainty is part of the result

A.U.R.O.R.A. should be able to say:

Indeterminate

when the available evidence is insufficient.

A system that knows when it does not know is more useful than one that always produces an answer.

5. Every conclusion must be explainable

The system should eventually be able to answer:

"Why did you reach this conclusion?"

Rather than simply returning:

AI: 87%

it should provide the evidence contributing to that assessment.

Multimodal Analysis

The long-term architecture is designed to support multiple types of digital content.

                    DIGITAL ARTIFACT
                           │
             ┌─────────────┴─────────────┐
             │                           │
          ANALYSIS                   PROVENANCE
             │                           │
      ┌──────┼──────┐              ┌─────┼─────┐
      │      │      │              │     │     │
    Text   Image   Audio         Metadata Hash C2PA
      │      │      │
      └──────┼──────┘
             │
          Video
             │
           Code
             │
         Documents
             │
             ▼
      Evidence Fusion
             │
             ▼
     Probabilistic Report
Planned analysis modules
Text

Research areas include:

linguistic features;
lexical diversity;
syntactic structure;
n-grams;
perplexity;
burstiness;
stylometry;
embeddings;
supervised classification;
authorship comparison;
machine-translation detection;
human post-editing.
Images

Research areas include:

image statistics;
frequency-domain analysis;
noise patterns;
compression artifacts;
metadata;
EXIF;
visual inconsistencies;
embeddings;
neural classifiers;
manipulation detection;
partial generation;
provenance information.
Audio & Voice

Research areas include:

spectrograms;
spectral features;
MFCCs;
pitch;
prosody;
pauses;
background noise;
synthesis artifacts;
voice cloning;
voice conversion;
metadata.
Video

Research areas include:

frame analysis;
temporal consistency;
motion;
lighting;
physical consistency;
facial manipulation;
lip synchronization;
audio/video relationships;
compression;
metadata;
provenance.
Code

Research areas include:

AST analysis;
code stylometry;
naming patterns;
comments;
complexity;
structural similarity;
semantic similarity;
embeddings;
repository comparison;
Git history;
developer style;
temporal evolution.

The system will explicitly distinguish between:

Human-written
Human + AI assisted
AI-generated + human refactored
Primarily AI-generated
Indeterminate

where the available evidence permits such distinctions.

Evidence Fusion

One of the main research objectives of A.U.R.O.R.A. is determining how independent signals can be combined.

For example:

TEXT ANALYSIS
Synthetic probability: 0.72
Confidence: Medium

IMAGE ANALYSIS
Synthetic probability: 0.94
Confidence: High

AUDIO ANALYSIS
Synthetic probability: 0.19
Confidence: Medium

PROVENANCE
No verifiable provenance available

The final system should not simply calculate:

(0.72 + 0.94 + 0.19) / 3

Instead, it will investigate methods including:

ensemble models;
weighted evidence;
Bayesian inference;
late fusion;
early fusion;
calibration;
confidence estimation;
multimodal embeddings.

The final assessment should retain the individual evidence instead of hiding it.

Forensic Analysis

A.U.R.O.R.A. will also contain a forensic layer independent from machine-learning models.

Potential evidence includes:

SHA-256
File type
MIME type
Metadata
EXIF
Timestamps
Compression
File structure
Digital signatures
Content Credentials
C2PA
Fingerprints
Modification history

This distinction is fundamental.

A machine-learning model may determine:

"This image contains characteristics statistically associated with synthetic generation."

A provenance mechanism may determine:

"This asset contains verifiable information describing its creation history."

These are different forms of evidence.

Dataset Strategy

A detector is only as meaningful as the evaluation methodology behind it.

A.U.R.O.R.A. will therefore eventually maintain datasets containing:

Human-generated content
human-written text;
photographs;
recordings;
videos;
human-written code.
Synthetic content

Generated using multiple:

models;
generators;
versions;
configurations.
Hybrid content

Including:

AI → human editing
Human → AI assistance
AI → human rewriting
AI → translation
AI → compression
AI → screenshots
AI → reformatting
AI → code refactoring

The project will specifically investigate:

dataset leakage;
train/validation/test separation;
cross-model generalization;
unseen generators;
robustness;
adversarial modifications.
Evaluation

A.U.R.O.R.A. will not be evaluated by accuracy alone.

Metrics will include:

Accuracy
Precision
Recall
F1
ROC-AUC
PR-AUC
False Positive Rate
False Negative Rate
Confusion Matrix
Calibration
Robustness
Cross-model generalization

Particular importance will be given to false positives.

A system incorrectly accusing human content of being synthetic can be significantly more harmful than a system that simply refuses to make a confident classification.

Adversarial Testing

Once a detector exists, we will attempt to break it.

Controlled experiments will include:

Synthetic content
        │
        ├── compression
        ├── resizing
        ├── translation
        ├── rewriting
        ├── human errors
        ├── editing
        ├── format conversion
        └── recompression

The objective is not to create methods for evading real-world detection systems.

The objective is to understand how detection performance degrades under controlled transformations and use that knowledge to improve robustness.

All testing will be performed against datasets and systems for which experimentation is authorized.

Architecture

The long-term architecture is planned around independent analysis engines.

                         ┌───────────────┐
                         │     INPUT     │
                         └───────┬───────┘
                                 │
                         ┌───────▼───────┐
                         │    INGESTION  │
                         └───────┬───────┘
                                 │
                         ┌───────▼───────┐
                         │ MEDIA IDENTIFY│
                         └───────┬───────┘
                                 │
          ┌──────────┬───────────┼───────────┬──────────┐
          ▼          ▼           ▼           ▼          ▼
        TEXT       IMAGE       AUDIO       VIDEO       CODE
          │          │           │           │          │
          └──────────┴───────────┼───────────┴──────────┘
                                 │
                         ┌───────▼───────┐
                         │ FORENSIC      │
                         │ ANALYSIS      │
                         └───────┬───────┘
                                 │
                         ┌───────▼───────┐
                         │ PROVENANCE    │
                         │ ANALYSIS      │
                         └───────┬───────┘
                                 │
                         ┌───────▼───────┐
                         │ MODEL LAYER   │
                         └───────┬───────┘
                                 │
                         ┌───────▼───────┐
                         │ EVIDENCE      │
                         │ FUSION        │
                         └───────┬───────┘
                                 │
                         ┌───────▼───────┐
                         │ CALIBRATION   │
                         └───────┬───────┘
                                 │
                         ┌───────▼───────┐
                         │ EXPLANATION   │
                         └───────┬───────┘
                                 │
                         ┌───────▼───────┐
                         │ FORENSIC      │
                         │ REPORT        │
                         └───────────────┘
Development Roadmap

A.U.R.O.R.A. will be developed incrementally.

The project deliberately avoids implementing the entire architecture at once.

v0.0.1 — Foundation
repository structure;
Python package;
basic CLI;
file ingestion;
basic error handling;
first automated tests.
v0.0.2 — File Analysis
file identification;
metadata;
hashing;
basic forensic information.
v0.1.x — Forensic Engine
structured evidence;
forensic analyzers;
reproducible reports;
improved testing.
v0.2.x — First ML Detector

Text-based analysis using classical machine-learning methods.

v0.3.x — Scientific Evaluation
datasets;
train/test separation;
metrics;
calibration;
error analysis.
v0.4.x — Robustness

Controlled adversarial and transformation testing.

v0.5.x — Image Analysis

Computer-vision and image-forensics module.

v0.6.x — Audio Analysis

Audio and synthetic-voice analysis.

v0.7.x — Code Analysis

AST, stylometry and repository-based analysis.

v0.8.x — Documents

Multimodal document analysis.

v0.9.x — Multimodal Fusion

Combination of independent evidence sources.

v0.10.x — API

FastAPI-based analysis service.

v0.11.x — Security
untrusted file handling;
sandboxing;
authentication;
authorization;
rate limiting;
secrets management.
v0.12.x+

Infrastructure, experiment tracking, containers, CI/CD, monitoring and deployment.

v1.0.0

A complete research-oriented prototype capable of performing multimodal synthetic-content analysis with traceable evidence and calibrated probabilistic assessments.

Technology Stack

The stack will evolve with the project.

Core
Python
Git
GitHub
pytest
Data & Scientific Computing
NumPy
Pandas
SciPy
scikit-learn
Machine Learning
PyTorch
Hugging Face Transformers
Computer Vision
Pillow
OpenCV
Audio / Video
librosa
FFmpeg
NLP
spaCy
Transformers
Backend
FastAPI
Storage
SQLite during early development
PostgreSQL when project requirements justify it
Infrastructure
Linux
Docker
CI/CD
Experimentation

Potentially:

MLflow
DVC
other experiment/dataset management tools when justified.

No dependency will be introduced merely because it is popular.

Project Principles

A.U.R.O.R.A. follows a few rules throughout development:

Understand before implementing.

Measure before claiming.

Test before trusting.

Prefer evidence over intuition.

Prefer uncertainty over false certainty.

Prefer modularity over unnecessary complexity.

Document decisions.

Reproduce experiments.

Assume external files are untrusted.

Never confuse probability with proof.
Current Status

Early development — v0.0.1

The project is currently focused on its foundations.

The first objective is deliberately small:

Receive a digital artifact
        ↓
Analyze it safely
        ↓
Extract basic evidence
        ↓
Produce a reproducible result

Machine learning will come later.

Multimodal analysis will come later.

The first version of A.U.R.O.R.A. does not attempt to solve the entire problem.

It is building the foundation required to eventually study it properly.

Disclaimer

A.U.R.O.R.A. is a research and engineering project.

Synthetic-content detection is an inherently uncertain problem. Generative models evolve rapidly, transformations can destroy forensic signals, and content may be created through combinations of human and machine processes.

Therefore, A.U.R.O.R.A. is not intended to provide absolute proof of authorship or origin.

Its assessments should be interpreted as probabilistic evidence, together with their confidence, supporting signals and limitations.

Long-Term Vision

The ultimate goal is not to build a machine that simply answers:

"AI or human?"

The goal is to build a system capable of answering something much more useful:

"What can we determine about this artifact, what evidence supports that assessment, what evidence contradicts it, how confident are we, and what can we not determine?"

That is the problem A.U.R.O.R.A. is being rebuilt to investigate.

A.U.R.O.R.A.

The project begins with a file.

The objective is to understand its history.
