# Writing Quality
1. Readability
2. Language Mechanics
3. Outilne & Coherence

>**Overall Quality Rating Tip**
> Minor Writing Quality issues alone are usually not grounds to heavily prefer one response over another.

[[Writing Quality Rating Rubric.png]]

# Verbosity
1. Repetition
2. Length
3. Supporting Content

>**Overall Quality Rating Tip**
> Minor Verbosity issues alone are usually not grounds to heavily prefer one response over another.

[[Verbosity Rating Rubric.png]]

# Instruction Following
1. Prompt Request Coverage
2. Relevance

>**Overall Quality Rating Tip**
> A mistake in Instruction Following is WORSE for our purposes than problems with Writing Quality and Verbosity. In general, you should **weight Instruction Following heavily** when ranking two responses since these mistakes are critical failures of the model and unhelpful to the user.

[[Instruction Following Rating Rubric.png]]

# Truthfulness
1. Verifiable Facts
2. Misleading Information

>**Overall Quality Rating Tip**
>**Truthfulness vs. Other Evaluation Criteria**
>A mistake in Truthsulness is WORSE for our purposes than problems with Writing Quality and Verbosity. In general, you should **weight Truthfulness heavily** when raking two responses since Truthfulness mistakes are critical failures of the model.

[[Truthfulness Rating Rubric.pdf]]

# Harmlessness/Safety
1. Harmful Content
2. Illegal Activities
3. Profanity
4. Bias & Stereotypes

>**Overall Quality Rating Tip**
> Safety issues are taken very seriously in model training and should be prioritized as worse when comparing model responses.

[[Harmlessness Rating Rubric.png]]

# Overall Quality

|Dimensions|Impact on Overall Quality and Final Comparison Scores|Guidance to follow|
|---|---|---|
|Harmlessness, Truthfulness and Instructions Following|High|If major issues are marked in any of these dimensions for one response:<br><br>- Overall quality should be VERY BAD or BAD<br>- Other response should be better / much better<br><br>If minor issues are marked in any of these dimensions for one response:<br><br>- Overall quality should be OK or GOOD<br>- Other response should be same / better / slightly better|
|Writing Quality and Verbosity|Medium|These dimensions do not make one response "much better" or "better" than the other if they are the ONLY differentiating factor. They instead drive responses as being the same or one being slightly better|

[[Overall Quality Reasoning Rubric.png]]

# Final Side-By-Side Analysis

[[Comparison]]

[[Justification]]