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

## 🧠 Design Intent

This system was designed with a simple idea:

Most people don’t lack discipline — they lack awareness of patterns in their daily decisions.

Instead of asking users to "improve productivity",
this system helps them observe:

- where attention goes automatically
- where control is actually present
- what patterns repeat without awareness

The goal is to make reflection structural, not emotional.

---

## 🧠 Overview

This project translates decision-tree logic from machine learning into a behavioral reflection system for humans.

A decision tree is a flowchart-like structure where each question leads to different outcomes based on responses.

This project adapts that concept into a **human self-awareness system**.

Instead of classifying data, this system helps users:
- recognize their personal agency (control over actions)
- filter meaningful vs distracting inputs
- diagnose underlying causes of behavior and energy

---

## 🧩 System Design

The system operates as a structured reflection loop:

### 1. Perception Layer
Captures daily experiences and attention patterns

### 2. Decision Layer
Uses branching questions to classify:
- attention quality
- level of control (agency)
- underlying causes

### 3. Insight Layer
Converts responses into:
- awareness of behavior patterns
- recognition of control points
- identification of hidden influences

---

## 🌍 Core Idea

This system is inspired by two real-world decision systems:

### 📧 Spam Filtering → Attention System
Humans constantly filter attention like email systems filter spam.

👉 Reflection:
- What did I treat as “important” today?
- What was actually noise?

---

### 🏥 Disease Diagnosis → Root Cause Thinking
Medical systems identify root causes behind symptoms.

👉 Reflection:
- What caused my low energy or distraction?
- What patterns shaped my outcomes?

---

## 🌳 1. Attention & Distraction Awareness (Spam Filter Lens)

Q1: What distracted you today that your brain still treated as priority?

- Mostly meaningful focus →  
  ✔ Insight: Your attention system is well aligned  
  → Q2

- Mixed attention →  
  ✔ Insight: Your brain is partially filtering signal vs noise  
  → Q2

- Mostly distractions →  
  ✔ Insight: Noise was mistaken as importance  
  → Q2

---

## 🌳 2. Agency & Control Awareness

Q2: Which moment today could have gone differently if you had taken control?

- I can identify clear moments →  
  ✔ Insight: You had active control over your day  
  → Q3

- Not sure →  
  ✔ Insight: Many decisions happen on autopilot  
  → Q3

---

## 🌳 3. Root Cause Diagnosis

Q3: What was the hidden cause behind your focus shifting today?

- External environment →  
  ✔ Diagnosis: Outside conditions influenced behavior  

- Internal state (energy/mood) →  
  ✔ Diagnosis: Internal condition shaped focus  

- No clear cause →  
  ✔ Diagnosis: Pattern is still unconscious  
  → Q4

---

## 🌳 4. Growth Awareness

Q4: What did you handle today that felt easier than before — even slightly?

- Yes, improvement noticed →  
  ✔ Insight: Subtle growth is happening  

- Not sure →  
  ✔ Insight: Growth is often invisible day-to-day  

---

## 🌳 Final Output

The system generates:

- 🧠 Agency Awareness Level (High / Medium / Low)
- 🎯 Attention Quality (Focused / Mixed / Distracted)
- 🔍 Root Cause Insight (External / Internal / Unconscious)

### 🌱 Final Insight:
“Your day is not random — it is a sequence of small decisions shaped by attention, awareness, and internal states.”

---

Built as a behavioral reflection system combining decision-tree logic with human cognitive patterns.

## 🌊 Flowchart Representation

```mermaid
flowchart TD

A[User Reflection Begins] --> B{What distracted you today that your brain treated as priority?}

B -->|Meaningful focus| C[Aligned attention]
B -->|Mixed| D[Partial filtering]
B -->|Distractions| E[Noise dominance]

C --> F{Which moment could you have taken control?}
D --> F
E --> F

F -->|Clear moment| G[High agency]
F -->|Not sure| H[Autopilot behavior]

G --> I{What caused your focus shift?}
H --> I

I -->|External| J[Environment influence]
I -->|Internal| K[Emotional influence]
I -->|Unknown| L[Unconscious pattern]

J --> M[Final Reflection]
K --> M
L --> M
