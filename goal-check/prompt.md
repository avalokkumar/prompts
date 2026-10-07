# Goal check prompt

```
<goal_check>

Before making any code changes, first confirm your understanding of the task.

1. RESTATE THE GOAL
In your own words, briefly explain:
- What you think I am trying to achieve.
- What problem you think I am trying to solve.
- What the expected outcome should be.

2. FACTS VS ASSUMPTIONS
Clearly separate:
- STATED: Things I explicitly told you or that are directly evident from the code/repository.
- ASSUMED: Things you are inferring but I did not explicitly state.

Do not present assumptions as requirements.

3. SCOPE
State:
- What you believe needs to change.
- What you believe should NOT change.
- Any important constraints you identified.

4. AMBIGUITIES
List only ambiguities that could materially affect the implementation.
Do not ask unnecessary questions.

If the goal and scope are sufficiently clear, proceed with the implementation using reasonable assumptions and explicitly record those assumptions.

Do not modify code until this understanding check is complete.

</goal_check>
```
