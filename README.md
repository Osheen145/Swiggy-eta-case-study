📌 **Project Overview**

Swiggy ETA Detective is an independent product management case study focused on identifying delivery experience issues and proposing solutions to improve customer trust in delivery estimates.

I analyzed 100 customer reviews, identified recurring friction points, developed product hypotheses, prioritized potential solutions, and designed an A/B testing framework.

🎯 **Problem Statement**

Unpredictable delivery estimates can create uncertainty for customers ordering food. This case study explores customer-reported delivery issues and investigates how better ETA communication could improve the experience.

🔍 **Customer Research & Key Findings**

I analyzed 100 customer reviews and grouped them into four major friction themes:

Customer Pain Point	Share of Reviews
ETA Creep & Volatility	47%
Missing Items & Bot Friction	20%
Rider Stagnation at Kitchen	17%
Payment & Technical Glitches	16%

Key insight: ETA creep and volatility were the largest observed friction theme in the review sample.

💡 **Proposed Product Solutions**

Based on the review analysis, I developed three product ideas:

Confidence-Window ETA: Show customers an expected delivery time range instead of a single precise time.
Proactive Delay Communication: Notify customers when delivery estimates change.
Kitchen Rush Signal: Explore operational signals that could help identify potential preparation delays.

These are proposed solutions, not features confirmed to exist in Swiggy's product.

📊 **Feature Prioritization**

I prioritized the proposed features based on expected customer impact, implementation effort, and operational dependencies.

Feature	Priority
Confidence-Window ETA	P0
Proactive Delay Communication	P0
Kitchen Rush Signal	P1

🧪 **A/B Testing**

I designed an experiment to evaluate whether displaying an ETA range improves customer experience.

Control: A single ETA (e.g., arriving in 32 minutes).
Variant: An ETA range (e.g., expected between 28–36 minutes).
Primary metric: Percentage of orders delivered within the communicated ETA window.
Secondary metric: Post-delivery customer satisfaction.
Guardrail metrics: Checkout conversion and order cancellation rate.

The proposed decision rule is to continue with the variant if ETA accuracy improves without meaningful deterioration in the guardrail metrics.

🛠️ **Skills Demonstrated**
Customer research and review analysis
Problem identification
Product hypothesis development
Feature prioritization
Product metrics
A/B test design
Product thinking

🌐 **Project Links**
Live Case Study: https://osheen145.github.io/Swiggy-eta-case-study/
