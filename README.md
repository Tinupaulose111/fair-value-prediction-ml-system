
# Fair Value Prediction – Production ML System

A production-grade machine learning system for intrinsic stock value estimation, featuring drift detection,
automated retraining , replace old model with new and cloud-based inference.

[![CI/CD — API Service](https://github.com/Tinupaulose111/Fair_value/actions/workflows/api-cicd.yml/badge.svg)](https://github.com/Tinupaulose111/Fair_value/actions/workflows/api-cicd.yml)
[![Drift Detection (Weekly)](https://github.com/Tinupaulose111/Fair_value/actions/workflows/drift.yml/badge.svg)](https://github.com/Tinupaulose111/Fair_value/actions/workflows/drift.yml)
[![Model Retrain & Deploy (Triggered by Drift)](https://github.com/Tinupaulose111/Fair_value/actions/workflows/trainer.yml/badge.svg)](https://github.com/Tinupaulose111/Fair_value/actions/workflows/trainer.yml)

## Note on Source Code

The full implementation of this project is maintained in a private repository
due to deployment credentials and intellectual property constraints.

This public repository serves as a **system-design and production-workflow showcase**,
including architecture, automation logic, and execution proof.

## Business Problem

Retail investors often rely on multiple complex financial ratios (EPS, Book Value, Cash Flow, etc.)
to estimate intrinsic stock value, which increases decision complexity and risk.

This project simplifies the process by learning a **data-driven intrinsic value**
from multiple financial indicators, aligned with **value-investing principles**
to support lower-risk, long-term investment decisions.

## Solution Overview

The system continuously learns from financial data and automatically adapts
to changing data distributions using drift detection and retraining automation.

Key characteristics:
- Multi-factor intrinsic value modeling
- Automated drift detection (KS test)
- retraining and deployment
- old model replacement
- Cloud-hosted inference API

  ## System Architecture

![Fair Value ML System Architecture](architecture/fairvalue_flowchart.png)

*High-level architecture showing data ingestion, drift detection, automated retraining, and deployment on Oracle Cloud VM.*


