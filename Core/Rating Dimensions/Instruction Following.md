Assessing Instruction Following is a critical part of these tasks. Ultimately, we want to ensure that model responses follow the user's requests or directions. We think about Instruction Following in two ways:
1. Prompt Request Coverage
2. Relevance

# 1. Understanding Prompt Coverage

## What is Prompt Request Coverage? ("Coverage")
**Coverage** is simply an assessment of whether the generated response did everything the prompt asked it to do, even if its implicit.

- When asking for a list of edible foods starting with "A", does the response match those requirements? Does it list any foods that start with a different letter?
- When asked for a 6-week exercise routihe, does the response adhere to the timeframe? Does it give a much shorter program?

## How to Evaluate Coverage
Think about all the things the prompt asks for, and think about what the most important requests or constraints are that the prompt makes:

- **Hierarchy of Requests**: imagine a prompt requests a 500-word short-story about flying fish. Let's say one response offers a 400-word short-story about flying fish and another response offers a 500-word short story about sidh that don't fly. Which response would a user probebly prefer? Likely the former. We might consider the first response to have a Minor Issue, but the second response to have a Major Issue.
- **Going Above and Beyond**: oftentimes you will see model responses that provide a lot of additional information than what was specifically requested. That additional information may or may not be useful for the user (and could make one response slightly more helpful than the other), but it's important to prioritize instruction following over usefulness to maintain focus on the request.

# 2. Understanding Relevance

## What is Relevance?

Relevance is how we measure whether aspects of the model response do not relate at all to what was asked. Sometimes there are responses where the instructions may have been followed, but parts of the response are not relevant to addressing the tasks at hand.

## How to Evaluate Relevance

- Is a response almost entirely on point but also includes a tidbit that does not seem related or helpful to know? Minor Issues.
- Does the response include a bunch of irrelevant and unhelpful information? Major Issues.

---

> [!important]
> A mistake in Instruction Following is WORSE for our purposes than problems with Writing Quality and Verbosity. In general, you should **weight Instruction Following heavily** when ranking two responses since these mistakes are critical failures of the model and unhelpful to the user.

---

# Instuction Following Rating Rubric
![[Instruction Following Rating Rubric.png]]

# Relevant Files

## Instruction Following Rating Examples
![[Instruction Following Rating Examples.pdf]]

## Instruction Following Justification Example
![[Instruction Following Justification Example.pdf]]