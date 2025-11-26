## Goal
Demonstrate how refining a prompt using:
- SYSTEM (role & tone),
- USER (task & constraints),
- FEW-SHOT (example-guided formatting),

produces a highly controlled, consistent, and professional output.

Topic used in this study:
**Evolution (Biological Evolution)**

---

## 1. System Message (Role & Tone)

    [SYSTEM]:
    You are an experienced biology content writer.
    Your explanations are objective, clear, and scientifically accurate.

The SYSTEM message defines the model’s identity and ensures a consistent tone.

---

## 2. User Message (Task & Constraints)

    [USER]:
    Task: Summarize the following text in 3 bullet points.
    Tone: Objective, simple, scientific.
    Constraints:
    - Each bullet must be a maximum of 15 words.
    - No unnecessary details.

    Text:
    "Evolution is the process in which genetic characteristics of biological populations change across generations.
    Evolution occurs through mechanisms such as natural selection (including sexual selection) and genetic drift,
    altering genetic diversity. Some traits become more common while others decrease over generations.
    The evolutionary process has generated biological diversity at every organizational level."

The USER message defines the exact task, tone, and structural constraints.

---

## 3. Few-Shot Example (Teaching the Model the Output Pattern)

Example input:

    DNA carries hereditary information in the cell.

Example output:

    • DNA stores hereditary information.
    • It forms the basis of genetic transmission.
    • It exists in all living organisms.

Few-shot examples guide the model toward the desired output format and tone.

---

## 4. Final Assistant Output (Refined Prompt Result)

    • Evolution is a biological process where genetic traits change across generations.
    • Natural selection and genetic drift significantly influence population-level genetic diversity.
    • Evolution shapes biological diversity across every level of organization.

---

## 5. Why This Output Is High Quality

- Fully objective and scientific tone  
- Each bullet respects the 15-word constraint  
- High information density, yet easy to read  
- Structure consistently follows the few-shot pattern  
- No unnecessary explanations  

---

## 6. Conclusion

This refined prompt demonstrates how combining:
- SYSTEM → role and tone  
- USER → task and constraints  
- FEW-SHOT → example-guided formatting  

results in controlled, repeatable, and professional AI outputs.

Refined prompt design is a core skill in advanced Prompt Engineering and should be included in any serious portfolio.

