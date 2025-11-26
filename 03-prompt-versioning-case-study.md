# Prompt Versioning Case Study — V1 → V2 → V3 Improvement Workflow

## Goal
Demonstrate how prompt versioning works by iteratively improving a prompt (Version 1 → Version 2 → Version 3) to produce more professional, structured, and academic results.

---

## 1. Scenario
We create a prompt that explains a topic in 3 bullet points.  
Then we improve structure, tone, clarity, and constraints across versions.

Topic used in this study:

**“Why does social media addiction occur?”**

---

## 2. Version 1 — Basic Prompt (Simple, Not Professional)

**Prompt – V1**

    [SYSTEM]: You are an expert who gives simple explanations.

    [USER]:
    Why does social media addiction occur?
    Write 3 bullet points.

**Assistant Output – V1**

    • Frequent dopamine stimulation from social media can create habitual use.
    • Feelings like loneliness or boredom increase the urge to use social platforms.
    • Notifications and likes encourage users to return more often.

### V1 Evaluation
- ✔ Correct  
- ✔ 3 bullets  
- ✘ Too shallow  
- ✘ Not academic  
- ✘ Not suitable for a professional portfolio  

---

## 3. Version 2 — More Professional, Structured, With Constraints

**Prompt – V2**

    [SYSTEM]: You are an expert who explains scientific topics in a clear but detailed way.

    [USER]:
    Task: Explain the causes of social media addiction.
    Format: 3 bullet points.
    Tone: objective and informative.
    Constraint: each bullet must be at least 15 words.

**Assistant Output – V2**

    • Social media platforms trigger dopamine release through notifications and reward systems, creating a repetitive behavior loop.
    • Psychological factors such as anxiety, loneliness, and low self-esteem increase reliance on social platforms for validation.
    • Features like infinite scroll, autoplay, and personalized algorithms extend usage by reducing cognitive effort.

### V2 Evaluation
- ✔ Detailed  
- ✔ Scientific tone  
- ✔ Constraints applied  
- ✔ Professional  
- ✘ Still not “fully academic”  

---

## 4. Version 3 — Academic, High-Quality Output (Portfolio-Ready)

Chosen style:

**A → Bullets should be more academic**

**Prompt – V3**

    [SYSTEM]: You are a scientific content writer with an academic and disciplined style.

    [USER]:
    Task: Explain the core causes of social media addiction at an academic level.
    Tone: scientific, objective, contextual.
    Constraints:
    - 3 bullets.
    - Each bullet at least 18 words.
    - Use terminology from psychology and behavioral science.
    - Academic but still clear.

**Assistant Output – V3 (Academic Version)**

    • Social media addiction is associated with neurobiological reinforcement processes, where inconsistent feedback patterns activate dopamine pathways and strengthen repetitive behavioral tendencies over time.
    • Psychosocial mechanisms such as social comparison, belonging needs, and external validation seeking contribute to prolonged engagement and internalization of addictive usage patterns.
    • Algorithmically optimized feeds, infinite scrolling, and personalized recommendation systems disrupt attentional regulation, distort time perception, and significantly extend overall platform usage duration.

---

## 5. V1 → V2 → V3 Comparison Table

    Version | Tone         | Info Level | Constraint Use | Professionalism
    ------- | ------------ | ----------- | -------------- | ----------------
    V1      | Simple       | Low         | None           | Beginner
    V2      | Informative  | High        | Yes            | Intermediate
    V3      | Academic     | Very High   | Strict         | Portfolio-grade

---

## 6. Conclusion
This case study demonstrates how prompt versioning improves quality:
- V1 → basic clarity  
- V2 → structured, constrained, informative  
- V3 → academic, contextual, high-value output  

Prompt versioning is a core skill in professional Prompt Engineering and essential for producing consistent, high-quality AI behavior.
