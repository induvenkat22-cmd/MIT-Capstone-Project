# Real-Time Retail Feedback Intelligence
### A Generative AI-Powered Customer Feedback Intelligence Solution for Fashion Retail

**MIT Professional Education | Applied Artificial Intelligence and Data Science | Capstone Project**

---

## 1. Project Overview

Real-Time Retail Feedback Intelligence is a Generative AI-powered solution designed to help fashion retailers analyze customer feedback, understand sentiment, identify recurring product-related issues, and transform unstructured customer reviews into actionable business insights.

The project explores how Large Language Models (LLMs) and prompt engineering techniques can automate customer feedback analysis, generate structured insights, and support data-driven retail decision-making.

The business scenario focuses on ChicStyle, a fashion retailer experiencing significant increases in customer reviews during seasonal and holiday sales.

The proposed solution demonstrates how Generative AI can help retailers move beyond traditional manual review analysis towards automated, scalable, and intelligent customer feedback management.

## 2. Business Problem

Fashion retailers receive large volumes of customer reviews across multiple products and categories.

Manually analyzing this feedback is time-consuming, inconsistent, and difficult to scale, particularly during peak shopping seasons.

Consequently, important customer concerns involving product sizing, fabric quality, product descriptions, delivery experiences, and overall customer satisfaction may go unnoticed.

The business needs an intelligent solution that can:

- Process large volumes of customer reviews efficiently.
- Identify customer sentiment and recurring product issues.
- Generate meaningful summaries of customer feedback.
- Identify urgent customer concerns.
- Provide actionable insights to retail stakeholders.
- Support timely and informed business decisions.

The project addresses these challenges by exploring a Generative AI-powered approach to customer feedback intelligence.

## 3. Project Objectives

The primary objectives are to:

- Perform Feature Engineering and Exploratory Data Analysis (EDA) to understand customer behavior, review patterns, and product performance.
- Analyze customer reviews using Generative AI.
- Classify customer sentiment as Positive, Negative, or Neutral.
- Identify product-related issues and feedback categories.
- Generate concise summaries of customer feedback.
- Classify feedback based on urgency.
- Generate personalized customer responses.
- Provide actionable insights for retail business teams.
- Predict whether customers recommend a product.
- Evaluate different prompt engineering strategies and model performance.
- Assess API usage and associated costs to understand the operational feasibility of the solution.

## 4. Dataset

**Dataset:** Women's E-Commerce Clothing Reviews

The project uses customer reviews and associated product information to understand customer preferences, satisfaction levels, and product-related concerns.

The dataset includes information such as:

- Clothing ID
- Customer age
- Review title
- Review text
- Product rating
- Recommendation indicator
- Positive feedback count
- Product division
- Product department

The dataset supports exploratory data analysis, feature engineering, sentiment analysis, product issue identification, and recommendation prediction.

## 5. Technologies and Analytical Techniques

| Category | Technologies / Techniques |
|---|---|
| Artificial Intelligence | Generative AI |
| Language Models | Large Language Models (LLMs) |
| Programming | Python |
| Development Environment | Jupyter Notebook / Google Colab |
| AI Integration | OpenAI API |
| Data Analytics | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Feature Engineering | Data Transformation and Feature Preparation |
| Prompt Engineering | Zero-Shot, Few-Shot, Chain-of-Thought |
| AI Evaluation | LLM-as-a-Judge |
| Model Evaluation | Accuracy, Precision, Recall, F1-Score |
| Business Analytics | Exploratory Data Analysis and Business Insights |

## 6. Project Methodology

The project follows a structured analytical and Generative AI development approach.

### Phase 1: Business Problem Understanding

Understand the challenges faced by fashion retailers in processing large volumes of customer reviews and identify opportunities for automation through Generative AI.

### Phase 2: Data Understanding and Exploratory Data Analysis

- Understand the dataset structure and underlying business context.
- Examine customer reviews, ratings, and product categories.
- Perform exploratory data analysis to identify customer behavior and review patterns.
- Analyze rating distributions and potential class imbalances.
- Identify recurring themes in positive and negative customer feedback.

### Phase 3: Feature Engineering and Data Preparation

- Perform feature engineering to derive relevant analytical attributes.
- Clean and prepare customer review data.
- Transform and organize relevant features for downstream analysis.
- Prepare data for Generative AI-based feedback analysis and recommendation prediction.

### Phase 4: Generative AI and Prompt Engineering

Design, implement, and refine different prompting strategies to analyze customer reviews.

Three primary prompting approaches were explored:

**Zero-Shot Prompting**
- Generates predictions using instructions without providing examples.
- Establishes a baseline for Generative AI-based review analysis.

**Few-Shot Prompting**
- Provides sample inputs and expected outputs to guide model responses.
- Helps improve consistency and structured output generation.

**Chain-of-Thought Prompting**
- Encourages structured reasoning when interpreting customer feedback.
- Helps address nuanced sentiment and contextual information.

Both baseline (V1) and enhanced (V2) prompt versions were developed and evaluated.

### Phase 5: Structured Customer Feedback Analysis

Use Generative AI to transform unstructured customer reviews into structured information.

The generated outputs include:

- **Sentiment:** Positive, Negative, or Neutral.
- **Category:** Product or department associated with the review.
- **Feedback Summary:** Concise summary of customer feedback.
- **Urgency Level:** High, Medium, or Low.
- **Personalized Message:** Customer-oriented response based on the feedback.
- **Insights for Retail Teams:** Actionable recommendations derived from customer reviews.

### Phase 6: AI-Assisted Review Benchmark Testing

Conduct structured benchmark testing to compare the effectiveness of different Generative AI prompting strategies.

The benchmarking framework includes:

- Testing Zero-Shot, Few-Shot, and Chain-of-Thought prompting strategies.
- Comparing baseline (V1) and enhanced (V2) prompt versions.
- Evaluating generated outputs using a stratified sample of 50 customer reviews.
- Applying an AI-assisted evaluation framework using LLM-as-a-Judge.
- Comparing average judge scores across the different prompt versions.
- Assessing output quality, consistency, and reliability.
- Identifying the best-performing prompting strategy.

The benchmark results identified Few-Shot V2 (FS2) as the strongest-performing approach, achieving an average judge score of 0.9843.

### Phase 7: API Usage and Cost Analysis

Evaluate API consumption and associated costs during Generative AI experimentation and model evaluation.

The analysis considers:

- API usage during prompt development and experimentation.
- Token consumption associated with model interactions.
- API calls generated during repeated prompt evaluations.
- Cost implications of different prompting strategies.
- Budget constraints and cost management during experimentation.
- The relationship between model performance, API consumption, and operational cost.

This analysis provides an additional perspective on the economic feasibility and potential scalability of the proposed solution.

### Phase 8: GenAI-Powered Product Recommendation Classification

Develop a prompt-based binary classification approach to predict whether a customer recommends a product.

The classification output is:

- **1 – Recommended**
- **0 – Not Recommended**

The model evaluates customer review text and generates a recommendation prediction with a supporting explanation.

Performance is assessed using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

### Phase 9: Business Insights and Recommendations

Translate customer feedback patterns and Generative AI outputs into actionable recommendations for retail stakeholders.

The recommendations focus on:

- Product quality and merchandising.
- Inventory planning.
- Customer experience management.
- Personalized shopping experiences.
- Delivery and operational improvements.

## 7. Key Exploratory Data Analysis Findings

The exploratory analysis identified several important customer feedback patterns:

- Most reviewers fall within the 30–50 age range.
- Customer ratings are strongly positive, indicating an imbalanced dataset.
- Tops and Dresses receive substantial customer feedback.
- The Trend department shows comparatively lower customer satisfaction.
- Positive reviews frequently highlight comfort, fit, and fabric.
- Negative reviews commonly mention sizing problems, poor material quality, and mismatches between product images and actual products.

These findings highlight opportunities for targeted product improvements and better customer experience management.

## 8. AI-Assisted Benchmark Testing Results

Different prompt engineering strategies were benchmarked to identify the most effective approach for customer feedback analysis.

The evaluation compared six prompt versions across three prompting strategies.

### Average LLM-as-a-Judge Scores

| Prompt Strategy | Version | Average Judge Score |
|---|---|---:|
| Zero-Shot | ZS1 | 0.9686 |
| Zero-Shot | ZS2 | 0.9725 |
| Few-Shot | FS1 | 0.9784 |
| Few-Shot | FS2 | **0.9843** |
| Chain-of-Thought | COT1 | 0.9765 |
| Chain-of-Thought | COT2 | 0.9784 |

### Key Findings

- Few-Shot V2 achieved the highest average judge score of 0.9843.
- Enhanced prompt versions generally demonstrated improvements over their respective baseline versions.
- Few-Shot prompting demonstrated strong performance in generating consistent and structured outputs.
- FS2 was identified as
