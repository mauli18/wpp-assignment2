# Daily Reflection Simulation: Emotional Intelligence (EQ)
**Applicant:** Mauli Solanki
**Role:** Fellowship Assignment

## 1. Project Goal
To create a deterministic model for evaluating daily self-regulation and emotional triggers.

---

## 2. Deterministic Decision Tree Logic

### Level 1: Incident Identification
- **Q1: Did a specific event trigger a strong emotional response today?**
    - **YES** -> Go to Level 2 (Analysis)
    - **NO** -> Go to Level 1.1 (Maintenance)

#### Level 1.1: Maintenance (No Incident)
- **Q: Did you actively practice an EQ skill (e.g., active listening) today?**
    - **YES** -> Result: Positive Reinforcement.
    - **NO** -> Result: Goal for tomorrow: Intentional empathy.

---

### Level 2: Self-Awareness (The Pivot)
- **Q2: Were you aware of the physical/emotional trigger *while* it was happening?**
    - **YES** -> Result: High Self-Awareness. Proceed to Level 3.
    - **NO** -> Result: Awareness Gap. Proceed to Level 3.

---

### Level 3: Root Cause Analysis (Deterministic Outcomes)
**Based on the path taken above, identify the primary driver:**

1. **Physical/Environmental:** Was the reaction caused by lack of sleep, hunger, or external noise?
2. **Cognitive/Bias:** Was the reaction caused by a pre-existing assumption about the person/event?
3. **Skill-Based:** Did the reaction occur because you lacked a specific communication tool for that moment?

---

## 3. AI Guardrails & Instructions
To prevent hallucination, the following constraints are applied to the AI Agent:
- **Constraint 1:** Only ask ONE question at a time.
- **Constraint 2:** Do not provide emotional affirmations (e.g., "Good job!").
- **Constraint 3:** If the user provides a vague answer, ask for a binary (Yes/No) clarification.
