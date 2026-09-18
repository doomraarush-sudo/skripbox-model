# Scripbox Robo-Advisory AI Model

## AI in Digital Wealth Management — Scripbox Robo-Advisory Case Study

An end-to-end **AI/ML demonstration for digital wealth management**, modeled around a Scripbox-style robo-advisory workflow. The project combines customer risk profiling, mutual-fund ranking, personalized fund shortlisting, and SIP wealth projection.

> **Academic project:** The dataset used by the model is synthetic and is intended for demonstration and learning. It is not a production investment-advisory system.

## 🎯 Project Objective

The project demonstrates how an AI-driven wealth platform can transform:

**Client Data → Data Cleaning → Feature Engineering → Risk Prediction → Fund Ranking → Personalized Shortlist → SIP Projection**

The business problem addressed is the difficulty of manually profiling large numbers of investors and comparing a large mutual-fund universe consistently.

## 🤖 ML / AI Approach

### 1. Risk Profiling — Random Forest Classifier

A **Random Forest Classifier** predicts one of three investor risk categories:

* Conservative
* Moderate
* Aggressive

The model uses onboarding and behavioral indicators such as:

* Age
* Monthly income
* Dependents
* Investment horizon
* Monthly investable surplus
* Existing investments
* Reaction to a market drop

### 2. Explainable AI — Feature Importance

The model exposes **Gini feature importance** to show which inputs contrib
