# Solving problems and making decisions

**Covers:** Root cause, 5 Whys, Decision matrix, Confirmation bias, Sunk cost fallacy

## Fix the right thing, then choose well {#overview}
Two kinds of mistakes waste a lot of effort at work. One is fixing a symptom, so the problem comes back. The other is choosing an option for the wrong reasons, such as liking a familiar idea or refusing to give up on a bad one. This article covers two tools for the first problem and three ideas for the second.

## Root cause {#root-cause}
A root cause is the underlying reason a problem happens. The symptom is what you can see, such as a late delivery. The root cause is why: perhaps orders are entered by hand, and the hand-off is not checked. If you fix only the symptom, by shipping that one order faster, the next order is late again.

A useful test is: if I remove this cause, will the problem stop? If the answer is "maybe", you may still be looking at a symptom or a partial cause.

## 5 Whys {#5-whys}
The 5 Whys is a technique in which you keep asking "why?" until you reach the root cause. It was developed at Toyota by Sakichi Toyoda. Five is a rule of thumb, not a law: sometimes three questions are enough, sometimes seven are needed.

Rules for using it: base each answer on facts you can check, not guesses, and keep the question about processes, not people. "Why did Sam forget?" leads to blame. "Why does the process let a step be forgotten?" leads to a fix.

## Decision matrix {#decision-matrix}
A decision matrix is a table that scores each option against several criteria, with each criterion weighted by importance. It helps you compare options fairly when many factors matter.

Steps: list the options in rows and the criteria in columns, give each criterion a weight (for example out of 10), score each option from 1 to 5 against each, multiply score by weight, and add up each row. The highest total is a guide, not an order. If the result surprises you, ask whether a weight is wrong, because that surprise is useful information.

## Confirmation bias {#confirmation-bias}
Confirmation bias is the tendency to notice and believe information that matches what we already think, and to ignore or explain away what does not. Psychologist Peter Wason demonstrated it in 1960.

At work it appears when you search only for evidence that your plan will succeed, or when you read customer comments looking for praise. Guard against it by asking "what would prove me wrong?", by inviting someone to argue the opposite, and by writing down your prediction before you look at the data.

## Sunk cost fallacy {#sunk-cost-fallacy}
The sunk cost fallacy is continuing something because of what you have already spent, not because of what it will cost or give you from now on. The money, time and effort are gone either way, so they should not decide the next step.

Ask: "If I were starting today, with what I know, would I begin this?" If not, stopping may be the right choice. Teams that keep funding a failing project "because we have already invested so much" are making this error.

## A worked example {#example}
**5 Whys.** A website went down on Monday.
1. Why? The server ran out of disk space.
2. Why? Log files grew without limit.
3. Why? Nothing deleted old logs.
4. Why? The clean-up job was never set up on the new server.
5. Why? The setup checklist did not include it. **Root cause:** an incomplete checklist.

**Decision matrix.** Choose a tool for the team.

| Criterion (weight) | Tool A | Tool B | Tool C |
|---|---|---|---|
| Cost (5) | 4 | 2 | 3 |
| Ease of use (4) | 3 | 5 | 3 |
| Support (3) | 2 | 4 | 5 |
| **Weighted total** | 4x5+3x4+2x3 = 38 | 2x5+5x4+4x3 = 42 | 3x5+3x4+5x3 = 42 |

B and C tie at 42 and both beat A at 38. A tie is a signal to look at the weights or add a criterion, such as security, to separate them.

## A common mistake {#mistake}
Stopping the 5 Whys when you reach a person ("because Alex made an error"). That is rarely a root cause. Ask why the system allowed the error. Another mistake is using a decision matrix to justify a choice you have already made, by adjusting the weights until it wins.

## Key points {#key-points}
- Fix the root cause, or the problem returns.
- The 5 Whys means asking why repeatedly, based on facts and about processes.
- A decision matrix scores options against weighted criteria. Treat a tie as a prompt to think.
- Confirmation bias makes you seek only support for your view, so look for disconfirming evidence.
- Past spending is not a reason to continue, because the sunk cost fallacy points the wrong way.
