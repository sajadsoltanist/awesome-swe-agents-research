# Awesome SWE Agents Research

A curated collection of academic research papers, datasets, and models focusing on Software Engineering Agents powered by Large Language Models (LLMs).

## Overview
This repository aims to track and analyze the development of software engineering agents, with a particular focus on academic research and empirical evaluations. We emphasize real-world applications, reproducible research, and comprehensive benchmarking.

## Research Timeline

### 2024
- **[SWE-Gym]** (Pan et al., 2024)
  - First environment for training real-world SWE agents
  - 2,438 real Python tasks with executable environments
  - Introduced agent and verifier training methodology
  
- **[Commit0]** (Zhao et al., 2024)
  - **Task**: Automated library generation from scratch
  - **Contribution**: 
    - First benchmark focusing on complete library development
    - End-to-end evaluation of code generation capabilities
  - **Dataset**: 
    - Real-world open source Python libraries 
    - Includes full package structure and documentation
  - **Evaluation**:
    - Library functionality testing
    - Code quality assessment
    - Documentation completeness

### 2023
- **[SWE-Bench]** (Jimenez et al., 2024)
  - Large-scale benchmark for SWE agents
  - 19,008 training instances
  - Real-world GitHub issues

## Core Research Areas

### Training Environments
- **SWE-Gym** (Pan et al., 2024)
  - Executable environments with pre-installed dependencies
  - Real-world GitHub tasks
  - Unit test validation
  - Key stats: 2,438 tasks from 11 repositories

### Agent Architectures
1. **General-purpose Prompting**
   - OpenHands (Wang et al., 2024)
   - ReAct-style approaches
   - Long-horizon planning capabilities

2. **Specialized Workflows**
   - MoatlessTools (Orwall, 2024)
   - Predefined stages for code editing
   - Focused on specific task types

### Evaluation Metrics
- Resolve Rate (RR)
- Empty Patch Rate (EP)
- Pass@K and Best@K for trajectory evaluation

### Key Datasets
- **SWE-Gym**: 2,438 executable environments
- **SWE-Gym Lite**: 230 tasks for rapid prototyping
- **SWE-Gym Raw**: 66,894 instances spanning 358 repositories

## Benchmark Results

Key performance metrics on SWE-Bench Verified:
- OpenHands w/ Verifier (32B): 32.0%
- OpenHands Base (32B): 20.6%
- Baseline Models: See comparison table in Performance section

## Contributing

Please follow these guidelines when contributing:
1. Focus on peer-reviewed academic work
2. Include complete citation information
3. For new tools/models, include:
   - Model architecture details
   - Training methodology
   - Evaluation results
   - Reproduction instructions

## License

MIT License - see LICENSE file for details.
