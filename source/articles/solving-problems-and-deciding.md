# Solving problems and making decisions

**Covers:** Root cause, 5 Whys, Decision matrix, Confirmation bias, Sunk cost fallacy

## Fix the right thing, then choose well {#overview}
Two kinds of mistakes waste a lot of effort at work. One is fixing a symptom, so the problem comes back. The other is choosing an option for the wrong reasons, such as liking a familiar idea or refusing to give up on a bad one. In this article we will look at two tools for the first problem and three ideas for the second.

## Root cause {#root-cause}
Suppose a delivery arrives late. That is the symptom, the thing you can see. The root cause is the underlying reason it happens: perhaps orders are entered by hand, and the hand-off is not checked. If you fix only the symptom, by shipping that one order faster, the next order is late again.

A useful test is: if I remove this cause, will the problem stop? If the answer is "maybe", you may still be looking at a symptom or a partial cause.

## 5 Whys {#5-whys}
How do you dig down to the root? You keep asking "why?". That technique is the 5 Whys, developed at Toyota by Sakichi Toyoda. Five is a rule of thumb, not a law: sometimes three questions are enough, sometimes seven are needed.

Two rules for using it. Base each answer on facts you can check, not guesses. And keep the question about processes, not people. "Why did Sam forget?" leads to blame. "Why does the process let a step be forgotten?" leads to a fix.

## Decision matrix {#decision-matrix}
When many factors matter, a table helps you compare options fairly. A decision matrix scores each option against several criteria, with each criterion weighted by importance.

Here are the steps. List the options in rows and the criteria in columns. Give each criterion a weight (for example out of 10). Score each option from 1 to 5 against each criterion. Multiply score by weight, and add up each row. The highest total is a guide, not an order. If the result surprises you, ask whether a weight is wrong, because that surprise is useful information.

## Confirmation bias {#confirmation-bias}
We tend to notice and believe information that matches what we already think, and to ignore or explain away what does not. That tendency is confirmation bias. Psychologist Peter Wason demonstrated it in 1960.

At work it appears when you search only for evidence that your plan will succeed, or when you read customer comments looking for praise. Guard against it by asking "what would prove me wrong?", by inviting someone to argue the opposite, and by writing down your prediction before you look at the data.

## Sunk cost fallacy {#sunk-cost-fallacy}
Have you ever kept going with something only because you had already put so much into it? That is the sunk cost fallacy: continuing because of what you have already spent, not because of what it will cost or give you from now on. The money, time and effort are gone either way, so they should not decide the next step.

Ask: "If I were starting today, with what I know, would I begin this?" If not, stopping may be the right choice. Teams that keep funding a failing project "because we have already invested so much" are making this error.

## A worked example {#example}
**5 Whys.** A website went down on Monday.
1. Why? The server ran out of disk space.
2. Why? Log files grew without limit.
3. Why? Nothing deleted old logs.
4. Why? The clean-up job was never set up on the new server.
5. Why? The setup checklist did not include it. **Root cause:** an incomplete checklist.

**Decision matrix.** Let's choose a tool for the team.

| Criterion (weight) | Tool A | Tool B | Tool C |
|---|---|---|---|
| Cost (5) | 4 | 2 | 3 |
| Ease of use (4) | 3 | 5 | 3 |
| Support (3) | 2 | 4 | 5 |
| **Weighted total** | 4x5+3x4+2x3 = 38 | 2x5+5x4+4x3 = 42 | 3x5+3x4+5x3 = 42 |

B and C tie at 42 and both beat A at 38. A tie is a signal to look at the weights or add a criterion, such as security, to separate them.

## A common mistake {#mistake}
A common slip is stopping the 5 Whys when you reach a person ("because Alex made an error"). That is rarely a root cause. Ask why the system allowed the error.

A second slip is using a decision matrix to justify a choice you have already made, by adjusting the weights until it wins.

## Key points {#key-points}
- Fix the root cause, or the problem returns.
- The 5 Whys means asking why repeatedly, based on facts and about processes.
- A decision matrix scores options against weighted criteria. Treat a tie as a prompt to think.
- Confirmation bias makes you seek only support for your view, so look for disconfirming evidence.
- Past spending is not a reason to continue, because the sunk cost fallacy points the wrong way.
