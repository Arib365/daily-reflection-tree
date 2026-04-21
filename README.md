# 🌳 Daily Reflection Tree (AI-Inspired Psychological System)

## 🧠 Overview

This project is a decision-tree based reflection system designed to help users reinterpret their day through structured questions.

A decision tree is a flowchart-like structure where each question leads to different outcomes based on responses. :contentReference[oaicite:0]{index=0}  
This project adapts that concept from machine learning into a **human self-awareness system**.

Instead of classifying data, this system helps users:
- recognize their personal agency (control over actions)
- filter meaningful vs distracting inputs
- diagnose underlying causes of behavior and energy

---

## 🌍 Core Idea

This system is inspired by two real-world decision systems:

### 📧 Spam Filtering → Attention System
Just like email systems classify messages as spam or important, humans constantly filter attention.

👉 This system helps users reflect:
- What did I treat as “important” today?
- What was actually noise?

---

### 🏥 Disease Diagnosis → Root Cause Thinking
Medical systems diagnose diseases by identifying underlying causes of symptoms.

👉 This system helps users reflect:
- What caused my low energy or distraction?
- What patterns led to my outcomes?

---

## 🌳 1. Agency & Attention Awareness

Q1: What did your mind classify as “important” today?

- Mostly meaningful work →
    ✔ Insight: Your attention system prioritized value.
    → Q2

- Mixed (work + distractions) →
    ✔ Insight: Your attention filtering was partially effective.
    → Q2

- Mostly distractions →
    ✔ Insight: Your system misclassified noise as important.
    → Q2

---

## 🌳 2. Control & Decision Awareness

Q2: Where did you actively choose your response instead of reacting automatically?

- I can identify clear moments →
    ✔ Insight: You exercised control over your behavior.
    → Q3

- Not sure →
    ✔ Insight: Many decisions are subtle and go unnoticed.
    → Q3

---

## 🌳 3. Diagnosis (Root Cause Analysis)

Q3: What most influenced your focus or energy today?

- External distractions →
    ✔ Diagnosis: Environment influenced your attention

- Internal state (fatigue/mood) →
    ✔ Diagnosis: Energy and emotions shaped your performance

- Clear focus →
    ✔ Diagnosis: You maintained internal stability

---

## 🌳 4. Growth Reflection

Q4: What improved slightly compared to yesterday?

- I can identify improvement →
    ✔ Insight: Growth is happening incrementally

- No clear improvement →
    ✔ Insight: Stability is also part of growth

- Not sure →
    ✔ Insight: Growth is often invisible in the short term

---

## 🌳 Final Output

The system generates:

- 🧠 Agency Awareness Level (High / Medium / Low)  
- 🎯 Attention Quality (Focused / Mixed / Distracted)  
- 🔍 Root Cause Insight (Environment / Internal / Stable)  

### 🌱 Final Reflection Message:
“Your day was shaped by small decisions, filtered attention, and underlying patterns. Awareness of these gives you more control tomorrow.”

---

## 🌊 Flowchart Representation

```mermaid
flowchart TD

A[Start Reflection] --> B{What was important today?}

B -->|Meaningful| C[Good attention filtering]
B -->|Mixed| D[Partial filtering]
B -->|Distractions| E[Noise misclassified]

C --> F{Did you choose your responses?}
D --> F
E --> F

F -->|Yes| G[High agency]
F -->|No| H[Low awareness]

G --> I{What affected your energy?}
H --> I

I -->|External| J[Environment influence]
I -->|Internal| K[Emotional/energy cause]
I -->|Stable| L[Consistent performance]

J --> M[Final Reflection]
K --> M
L --> M
