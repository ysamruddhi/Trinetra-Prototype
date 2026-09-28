# Trinetra-Prototype

# TRINETRA: AI-Powered MPLADS Monitoring Prototype

SIH 2026 | Problem Statement SIH26102 | Team Code Crew

An interactive prototype of TRINETRA, a monitoring layer that flags
delayed, inconsistent or anomalous MPLADS projects and shows the reason
behind each flag.

## Live demo
(https://ysamruddhi.github.io/Trinetra-Prototype/)

## Demo video
[paste your YouTube link]

## What the prototype shows
- Role-based views: MP, District Authority, State Nodal, Ministry, Admin
- Map-based project view with risk tiers
- Explainable flags for each project

## Important note
The prototype uses **synthetic data** modeled on the MPLADS project
structure. The detection layer (rule engine + Isolation Forest) is
designed and being integrated; the flag reasons shown in the UI are
illustrative.

## Tech stack
React.js, JavaScript, HTML/CSS, Chart.js (prototype UI)
Planned backend: Python, FastAPI, PostgreSQL, scikit-learn
