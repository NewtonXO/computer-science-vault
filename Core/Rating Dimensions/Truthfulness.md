When training state-of-the-art AI models, it's extremely important to address factual errors or misinformation. LLMs are known to "hallucinate" or make up information that isn't true. It is your job to determine if a model response contains any factual inaccuracies.

We think about Truthfulness in two ways:
1. Verifiable Facts
2. Misleading Information

# Verifiable Facts

## What's a Verifiable Fact?
A verifiable fact is something that is true (or false) regardless of personal feelings, interpretations, or opinions. It can be confirmed by evidence or observation that is consistent and repeatable. Some examples are:

- George Washington was the first president of the United States (true)
- The Earth is flat (false)
- Spain is a city in Europe (false)

## How to Spot a Verifiable Fact
You can identify a verifiable fact by asking yourself: "is this statement or assertion definitively true or false?" Opinions, perspectives, feelings, etc. are **not** verifiable facts.

To be consided verifiable, a fact generally needs to be:
1. **Objective**: the fact should be independent of personal feelings or opinions.
2. **Observable**: there should be a way to observe or measure the fact.
3. **Repeatable**: the observations or measurements can be repeated by others with consistent results.

## How to Validate Whether a Verifiable Fact is True or False
- Google it! Or use your search engine of choice. Most of the time you will be able to clearly tell whether the fact is true or not. If you can't validate one way or the other, chances are the statement or assertion is not a verifiable fact.
- Check Your Sources: make sure the information is coming from and confirmed by multiple sources.
- Be wary of lists: sometimes a response will contain a lot of varifiable pieces of information, make sure to check each of them.

# 2. Misleading Information

## What is Misleading Information?
We define Misleading Information is anything presented as a verifiable fact that cannot actually be verified. Model responses may present opinions as verifiable facts, or assert as fact something that has no proof of being true (or false).

Consider the following examples:
- "Nike has the best running shoes." This is an opinion, since the definition of "best" is subjective.
	- By contrast: "Nike sells the most running shoes" is a statement that could be verified.
- "The vegan diet is the healthiest." This asserts as a facts something that cannot be wholly verified.
	- By contrast: "some people believe the vegan diet is healthiest" is a statement that could be verified.

---

>[!important]
>**Truthfulness vs. Other Evaluation Criteria**
>A mistake in Truthsulness is WORSE for our purposes than problems with Writing Quality and Verbosity. In general, you should **weight Truthfulness heavily** when raking two responses since Truthfulness mistakes are critical failures of the model.

---

# Truthfulness Rating Rubric
![[Truthfulness Rating Rubric.pdf]]

# Relevant Files

## Truthfulness Rating Examples
![[Truthfulness Rating Examples.pdf]]

## Truthfulness Justification Example
![[Truthfulness Justification Example.pdf]]