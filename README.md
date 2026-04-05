# Fraud Detection using AutoEncoder (PyOD)

## Overview
This project implements an anomaly-based fraud detection system using AutoEncoder from PyOD. The model is trained only on normal transactions and detects fraud based on reconstruction error.

## Dataset
Kaggle Credit Card Fraud Detection Dataset

## Setup

```bash
pip install -r requirements.txt
cd src
python3 train.py