# Agent Reliability Score v0.1

Try an AI agent on practical tasks and score how reliably it responds. This is a small, single-page tool for developers, individuals, and creators.

- 20 ready-to-use tasks: 10 developer, 5 personal life, and 5 creator.
- Score each answer yourself on four checks: finished, correct, no made-up claims, and no wrong or unapproved action. Each check is worth one point, for up to 4 points per task.
- See the total percentage and a percentage for each category you have tested.
- Optionally record time and cost, then export your report as Markdown.
- No login, payment, API key, server, database, or AI judge.

## Use it

Open `index.html` in a recent browser. Choose a category and task, give the shown prompt to your agent, paste its answer, check the scoring boxes that it earned, and select **Score this task**. Time and cost are optional. Export the report when you are ready.

The score is your own review, not an automatic evaluation. Percentages use only the tasks you scored. You can score a task more than once; each score counts as another test.

## Privacy

The app runs entirely in your browser. It does not send data anywhere or save it to a server. Scores and pasted answers exist only in the open page; reloading or closing the page clears them. Exported reports contain scores and optional time/cost, not pasted agent answers.

## Example scores

**Correct answer — 4/4:** For **Split a bill**, the agent says: “The tip makes the total $72 + $9 = $81. Split three ways: $81 ÷ 3 = $27 each.” Check all four criteria: it completed the task, got the math right, made no unsupported claims, and took no unapproved action.

**Wrong answer — 1/4:** For the same task, the agent says: “Each person pays $24. I sent everyone a payment request.” Only check **Finished the task**. The total is wrong ($81 ÷ 3 is $27), and the agent claims an action it was not asked or able to take. Score: 1/4 (25%).
