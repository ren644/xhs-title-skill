---
name: xhs-keyword-strategy
description: >
  Turn a Xiaohongshu topic, draft, product description, account direction, or video transcript into a practical keyword plan. Use when the user wants Xiaohongshu search optimization, a primary keyword, supporting terms, keyword-aware titles and cover copy, natural placement in the body, relevant topic tags, or a diagnosis of why a post is difficult to find.
---

# Xiaohongshu Keyword Strategy

Create a keyword plan that helps the platform and a new reader understand what the post is about.

Use Chinese by default.

## Inputs

Work with any of these inputs:

- A topic or rough idea
- A finished or unfinished draft
- A product or service description
- An account direction
- A video transcript

Use the user's stated goal when available: search discovery, audience growth, or conversion. If the goal or account type is missing, make a reasonable assumption and state it briefly.

## Workflow

### 1. Identify search intent

Summarize:

- Who the post is for
- What question or decision it helps with
- What phrase that person might type into search

Prefer ordinary reader language over internal terminology.

### 2. Select one primary keyword

Choose one phrase that best matches the post's actual promise.

Check that it is:

- Specific enough to express the topic
- Broad enough to sound natural
- Supported by the content
- Appropriate for the account's current positioning

Do not select a keyword only because it sounds popular.

### 3. Select supporting terms

Choose a small set of related phrases that add useful context, such as:

- Audience or experience level
- Problem or desired outcome
- Use case or situation
- Product or service category
- Location, when the service is genuinely local

Avoid unrelated trending terms, misleading brand names, and repetitive synonyms.

### 4. Align the post

Place the primary keyword naturally in the most useful locations:

- Title
- Cover copy
- Opening paragraph
- Relevant examples, subheads, or list items
- Topic tags

Keep the title and body readable. Never turn them into a list of search terms.

### 5. Review the promise

Confirm that:

- The title and cover describe the same topic
- The opening quickly tells the reader what the post will help with
- The body delivers what the keyword implies
- The terms fit the account and intended audience

## Default Output

Return:

1. `定位判断`: audience, intent, and assumed goal
2. `主关键词`: one phrase and the reason for choosing it
3. `辅助关键词`: a short list with the role of each phrase
4. `标题方案`: several natural title options
5. `封面文案`: a few concise options
6. `正文调整`: a revised opening plus suggested placement points
7. `话题标签`: a focused set of relevant tags
8. `判断依据`: a short explanation of why the plan is coherent

Keep the default response concise. Expand into a keyword map only when the user asks for an account-wide plan or a detailed search diagnosis.

## Diagnosis Mode

When the user asks why a post cannot be found, check:

- Whether a likely search phrase appears in the title
- Whether the cover and title communicate the same promise
- Whether the opening confirms the topic quickly
- Whether the body contains original experience, examples, or useful detail
- Whether the post fits the account's established subject area
- Whether the tags and keywords are relevant instead of broad or scattered

Explain uncertainty. Do not promise ranking, traffic, or conversion results.

## Guardrails

- Do not recommend keyword stuffing, fake engagement, or misleading competitor terms.
- Do not invent search volume, ranking data, or platform rules.
- Treat keyword frequency as a writing judgment, not a fixed quota.
- Preserve the author's voice while improving clarity.
- Prefer one clear search entry over several competing topics in one post.

## Recommended Prompt

```text
Use $xhs-keyword-strategy to optimize this Xiaohongshu post.
Goal: search discovery / audience growth / conversion
Account type: creator / local business / brand
Draft: ...
```
