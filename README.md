Reinforcement Learning for Pricing Optimization

Overview

This project implements a reinforcement learning model using Stable-Baselines3 and OpenAI Gym to optimize product pricing strategies based on historical sales data. The goal is to dynamically adjust product prices to maximize total revenue while considering various factors such as sales trends and conversion rates.

Features

Data Preprocessing: Cleans and prepares historical sales data for modeling.

Random Forest Model: Predicts sales based on pricing and seasonal trends.

Custom Gym Environment: Simulates a pricing environment for reinforcement learning.

PPO Model Training: Trains a Proximal Policy Optimization (PPO) agent to optimize pricing.

Reward Tracking: Monitors and logs reward components to understand agent behavior.

Loss Analysis: Tracks and visualizes loss and reward distributions over training episodes.

Usage

Load and preprocess sales data.

Train the Random Forest regression model for sales predictions.

Initialize the custom Gym environment with historical data.

Train the reinforcement learning agent using PPO.

Monitor training progress with reward breakdowns and loss analysis.

Evaluate the model and analyze pricing strategies.
