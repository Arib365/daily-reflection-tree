# 🌳 Daily Reflection Tree (AI-Inspired Psychological System)

## ❗ Why This Matters

Most people evaluate their day based on outcomes:
- "Did I finish tasks?"
- "Was I productive?"

This system challenges that approach.

It helps users see:
- the decisions they made (agency)
- what they paid attention to (signal vs noise)
- the hidden causes behind their behavior

The goal is not to judge the day, but to understand it.

---

## 🧠 Overview

This project is a decision-tree based reflection system designed to help users reinterpret their day through structured questions.

A decision tree is a flowchart-like structure where each question leads to different outcomes based on responses. :contentReference[oaicite:0]{index=0}  

This project adapts that concept from machine learning into a **human self-awareness system**.

Instead of classifying data, this system helps users:
- recognize their personal agency (control over actions)
- filter meaningful vs distracting inputs
- diagnose underlying causes of behavior and energy

---

## 🧩 System Design

This reflection model works in three layers:

### 1. Input Layer  
User experiences from the day (actions, attention, energy)

### 2. Classification Layer  
Inspired by AI systems:
- Spam Filtering → attention classification (signal vs noise)
- Diagnosis → root cause identification

### 3. Insight Layer  
Generates meaning:
- Where the user had control
- What influenced outcomes
- What can improve

This structure transforms reflection into a repeatable system.

---

## 🌍 Core Idea

This system is inspired by two real-world decision systems:

### 📧 Spam Filtering → Attention System
Just like email systems classify messages as spam or important, humans constantly filter attention.

👉 Reflection:
- What did I treat as “important” today?
- What was actually noise?

---

### 🏥 Disease Diagnosis → Root Cause Thinking
Medical systems diagnose problems by identifying root causes behind symptoms.

👉 Reflection:
- What caused my low energy or distraction?
- What patterns led to my outcomes?

---

## 🌳 1. Agency & Attention Awareness

Q1: If your attention worked like a spam filter today — what did it mistakenly mark as “important”?

- Mostly meaningful work →  
  ✔ Insight: Your attention system prioritized value  
  → Q2

- Mixed (work + distractions) →  
  ✔ Insight: Your filtering worked, but not consistently  
  → Q2

- Mostly distractions →  
  ✔ Insight: Noise was treated as signal  
  → Q2

---

## 🌳 2. Control & Decision Awareness

Q2: Where did you consciously choose your response instead of reacting automatically?

- I can identify clear moments →  
  ✔ Insight: You exercised control over your behavior  
  → Q3

- Not sure →  
  ✔ Insight: Many decisions are subtle and go unnoticed  
  → Q3

---

## 🌳 3. Diagnosis (Root Cause Analysis)

Q3: What most influenced your focus or energy today?

- External distractions →  
  ✔ Diagnosis: Your environment shaped your attention

- Internal state (fatigue/mood) →  
  ✔ Diagnosis: Energy and emotions influenced your actions

- Clear focus →  
  ✔ Diagnosis: You maintained internal stability

---

## 🌳 4. Growth Reflection

Q4: What improved even slightly compared to yesterday?

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
