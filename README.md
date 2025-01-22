# Multi-Armed Bandit Implementation for Ad Banner Optimization

## Project Overview
This project implements an Epsilon-Greedy Multi-Armed Bandit algorithm to optimize ad banner selection. It simulates a scenario with 5 different ad banners and uses the MAB approach to balance exploration and exploitation in determining the most effective banner for user engagement.

## Problem Statement
When running a website with multiple ad banner variations, traditional A/B testing requires complete exploration before making decisions, leading to potential lost opportunities. This implementation demonstrates how Multi-Armed Bandits can more efficiently:
- Identify high-performing banners faster
- Reduce opportunity cost during testing
- Adapt banner selection based on real-time performance

## Implementation Details

### Data Simulation
- Creates a synthetic dataset (100,000 rows × 5 banners)
- Each entry represents a user interaction (1 for click, 0 for no click)
- Simulates realistic ad banner performance scenarios

### Algorithm Components
```python
# Key Parameters
num_banner = 5                    # Number of different banners
no_of_iterations = 100000         # Total number of user interactions
epsilon = 0.5                     # Exploration-exploitation balance
