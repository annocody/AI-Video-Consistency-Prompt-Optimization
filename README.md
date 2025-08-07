# AI-Driven Character Consistency and Prompt Optimization in Video Generation

## Overview
This project aims to address key challenges in AI-generated video content, specifically character consistency and prompt optimization. It integrates video generation APIs, analyzes frame-level consistency, and iteratively improves prompts based on drift detection.

## Modules

### 1. api_integration
Handles communication with AI video generation APIs to submit prompts and retrieve generated videos.

### 2. frame_analysis
Extracts frames from videos and uses facial recognition to evaluate character consistency across frames.

### 3. report_generation
Generates visual and numerical reports highlighting consistency scores and drift frames.

### 4. prompt_optimization
Implements basic heuristics to refine prompts based on feedback from consistency analysis.

### 5. ui
Optional Streamlit-based interface for uploading videos, viewing reports, and interacting with the optimization loop.
