# EDTweet-ID
Eating Disorders Tweets - Indonesian Dataset

**EDTweet-ID** is a curated dataset of 3,044 Indonesian-language tweets collected from the X platform (formerly Twitter) between 2020 and 2025. The dataset aims to support research on eating disorders (EDs) in underrepresented languages, particularly Bahasa Indonesia.

## Dataset Description

Each tweet in the dataset is labeled into one of four categories:

| Category | Description |
|----------|-------------|
| **D (Dieting)** | Extreme dieting, fasting, calorie tracking, avoiding certain foods, compulsive exercise for weight loss |
| **B (Bulimia & Food Preoccupation)** | Bulimic behaviors, obsession with food, binge-eating, purging, guilt after eating |
| **O (Oral Control)** | Controlling overeating due to social pressure, shame of eating around others |
| **None** | Tweets not related to ED, such as jokes, celebrity news, or general mentions of food/weight without distress |

The annotation categories were developed with reference to the **Eating Attitudes Test (EAT-26)** and validated by a psychology expert.

## Annotation Process

- The annotation was performed in two stages:
  1. An initial subset of 200 tweets was labeled by three annotators.
  2. After validation, the remaining tweets were annotated accordingly.
- **Inter-annotator agreement** was calculated using **Fleiss’s kappa**, with a resulting value of **0.88**, indicating *almost perfect agreement*.

## Usage

This dataset is publicly available for **research purposes**. You may use it to:
- Train and evaluate machine learning models for ED detection
- Analyze ED discourse trends in Indonesian social media
