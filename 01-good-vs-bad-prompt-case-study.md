Prompt Engineering Case Study — Paulo Coelho
Goal
Demonstrate how defining the model’s role (system), the user’s task, and a clear output format leads to significantly higher-quality, structured, and consistent responses.

1. Bad Prompt Example
[USER]: Who is Paulo Coelho?

❌ Bad Output
Paulo Coelho is a famous writer from Brazil. He wrote The Alchemist and many other books. 
He is very popular around the world and his books talk about life and dreams. 
He also had different jobs before becoming a writer.

-Issues
-Inconsistent tone
Vague and generic information
-No structure or formatting
-Not objective or encyclopedic
-Not reproducible
-Lacks depth and clarity

2. Good Prompt Example
[SYSTEM]: You are an experienced encyclopedia writer.
[USER]:
Task: Provide information about an author.
Format: 3 bullet points.
Tone: Objective and concise.
Author: Paulo Coelho

✅ Good Output
• Brazilian novelist known for spiritual and philosophical themes, best recognized for “The Alchemist.”
• His works explore personal destiny, self-discovery, and human resilience, reaching global audiences in 80+ languages.
• Member of the Brazilian Academy of Letters since 2002 and one of the world’s best-selling contemporary authors.

-Strengths
-Clear and structured bullet points
-Objective, encyclopedia-style tone
-Focused directly on requested information
-Reproducible and professional
-Matches the role defined in the system message

3. Key Learnings

System message defines the model’s role → ensures consistent tone and style
Explicit user instructions (task + format + tone) improve structure and clarity
specific context (author name) directs the model and reduces ambiguity
Good prompts produce controlled, repeatable, high-quality outputs

4. Conclusion

Providing clear instructions—role, task, format, tone, and context—dramatically improves the accuracy, consistency, and structure of the model’s responses compared to short, vague prompts.
