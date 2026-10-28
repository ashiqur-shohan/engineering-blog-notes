# Technical Blog Reading Workflow

## Objective

Understand how experienced engineering teams solve real problems, identify gaps in my knowledge, and apply useful ideas to my own engineering work.

## Phase 1: Understand the Story

**Suggested time: 5–10 minutes**

Read the title, introduction, problem statement, section headings, conclusion, and relevant diagrams.

Don't stop to look up every unfamiliar word.

Before using AI, write a rough answer to these questions:

1. What problem was the company facing?
2. Why were existing solutions insufficient?
3. What did the company build or change?
4. What improved because of the solution?

Record what I understand and what remains unclear.

## Phase 2: Identify Knowledge Gaps

**Suggested time: 5–10 minutes**

List unfamiliar concepts that appear important to understanding the article.

Classify each concept:

- **Core:** Necessary to understand the problem or central solution.
- **Supporting:** Helps explain the solution but is not essential to the main idea.
- **Implementation detail:** Explains a particular technology or implementation choice.

Prioritize core concepts.

Learn enough to understand the article's main reasoning, then move to secondary details if needed.

## Phase 3: Understand the Solution

**Suggested time: 15–25 minutes**

The objective is to reconstruct the system in my own words. Could I build a small version of this idea with the technologies I already know?

Ask:

1. What are the main components?
2. What information flows between them?
3. What does each component do?
4. How does the solution address the original problem?
5. What evidence supports the claimed benefits?
6. What limitations or trade-offs are described?

Use a diagram when it helps clarify relationships.

Distinguish the actual architecture described by the authors from simplified diagrams created for learning.

## Phase 4: Verify My Understanding

Close the article and explain the following without looking at it:

- The original problem.
- The central idea of the solution.
- The most important technical concepts.
- One limitation or trade-off.

Compare my explanation against the article and authoritative documentation.

Use AI to identify gaps, challenge assumptions, and explain difficult concepts.

Do not treat an AI explanation as verified merely because it sounds convincing.

## Phase 5: Create or Update Notes

Use `templates/article-template.md` for article notes.

Use `templates/concept-template.md` for reusable technical concepts.

For each important concept:

1. Check whether a concept note already exists.
2. Update the existing note if appropriate.
3. Create a new note only when it adds distinct value.
4. Link the concept to the relevant article.
5. Record sources for important technical claims.

Keep article notes focused on the article. Keep reusable explanations in concept notes.

## Phase 6: Apply the Idea (Optional)

Ask:

Could I reproduce a small part of this idea using technologies I already know?

Choose an experiment only when it would meaningfully improve understanding or help with real engineering work.

Prefer small experiments over attempting to recreate an entire production system.

Record:

- What I tried.
- What I expected.
- What actually happened.
- What I learned.

An experiment is optional. Some articles are best understood through careful reading and explanation.