# AI Fundamentals & LLM Security – Notes
*Nov 5, 2026*

## AI concepts
- Machine learning: a model learns patterns from data and uses them to make predictions.
- Generative AI: a type of machine learning that creates new content. LLMs generate text by predicting the most probable next token.
- Token: a piece of text (a word or part of a word). Input and output are measured in tokens.
- Parameters: the internal values a model learned during training.

## OWASP Top 10 for LLM Applications (2026) – key risks
- LLM01 Prompt Injection: input that changes what the model does and how it interacts with the user. In my lab it was the hardest attack to pull off, but the most harmful when it works.
- LLM02 Sensitive Information Disclosure: the model reveals credentials or sensitive/personal information. Never put this kind of data in any prompt or setting.
- LLM08 Hidden Context Exposure: anything in the model's hidden context can be exposed.

## Lessons
- Give AI agents least privilege, and temporary access only when needed (LLM03 Excessive Agency).
- Keep the OWASP Top 10 for LLMs in mind when using or recommending AI in a company.
