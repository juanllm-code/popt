# POPT: The Preference-Optimized Policy Theorem

In the past few years, we have seen language models (LLMs) and vision models (LVMs) exhibit behaviors that seem strikingly goal-oriented, even though they were not explicitly trained with reinforcement learning. From persistent retries in AI testing (as seen in DragonCrawl) to OpenAI’s GPT agents handling multi-step instructions, the question arises: Why do these models appear to “want” something?

The answer lies in preference optimization. Models like GPT-4, Claude, and DeepSeek aren’t inherently goal-driven, but when optimized through preference-based objectives like Direct Preference Optimization (DPO) or General Reinforcement Preference Optimization (GRPO), they naturally converge to behaviors that maximize structured reward functions.

I went in depth in the mathematical formulations here: https://medium.com/@juan.sunnyvale/popt-the-preference-optimized-policy-theorem-b0ab20970518

This repo is WIP (mostly in my free time). There is a lot to be added here, but I will start with a colab
