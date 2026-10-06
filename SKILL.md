---
name: word-card
description: Turn a user-provided article or pasted text into 5–8 concise knowledge cards, each with a title, core knowledge, and an example sentence. Use when the user wants to study, review, or extract learning points from supplied reading.
---

# Word Card

Turn the article the user provides into **5–8 useful knowledge cards**. Treat the article as the source of truth; do not add unsupported facts or claim that an inference came directly from the article.

## Create the cards

- Read the full text first and identify its main ideas, terms, mechanisms, distinctions, and practical takeaways. Choose the most teachable, non-redundant points; do not simply make one card per paragraph.
- Use the same language as the article unless the user asks for another language.
- Make each card understandable on its own. Explain the central idea in plain, concise language, preserving important conditions or caveats from the text.
- Write one example sentence for each card. Prefer a sentence from the article when it clearly demonstrates the idea; otherwise write a short, concrete application sentence consistent with the article. Do not present an invented sentence as a quotation.
- Keep the total between 5 and 8 cards. Use 5 by default; use more when the article has enough distinct, valuable ideas to warrant them. Avoid padding with repetition or unsupported information. If the text is too short or incomplete to support five sound cards, ask for more text rather than inventing content.
- If the user specifies a card count within this range or a formatting preference, follow it.

## Output format

Start with a brief heading, then number the cards. Use exactly these fields for every card:

### 1. 标题
- **核心知识：** …
- **例句：** …

Translate the field labels to the output language when appropriate. Do not add an introduction, summary, or extra fields unless the user asks.
