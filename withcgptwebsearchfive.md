## Milestone 3 - Voice-first Learning Coach for Indian Students

### Solution to Designing and Building a Prototype: Voice-first Learning Coach for Indian Students

#### Task 5 - Define success metrics for the feature and outline what you would track.

**Success Metrics for the Voice-first Learning Coach**

For the solution we selected-**a Voice-first Learning Coach for Indian students** I would measure success at four levels:

**Discovery → Successful Voice experience → Repeat usage → Learning value**

The important distinction is that **Voice launches are not success.** We want students to successfully use Voice for learning and come back to it. A North Star should capture customer value and be supported by a small set of actionable input metrics.

OpenAI's existing Study Mode already supports step-by-step learning, questions, feedback, quizzes, study materials, and Voice interactions, so these metrics can focus specifically on whether Voice improves the learning experience.

#### 1. North Star Metric ⭐

**Weekly Repeat Voice Learning Users**

**Number of Indian student users who complete ≥2 meaningful Voice learning sessions within a 7-day period.**

**Why this metric?**

It captures three things simultaneously:

**Voice adoption + learning value + repeat behavior**

A user who merely taps the microphone once is not necessarily adopting Voice.

But a student who uses Voice twice in a week for learning has demonstrated:

**"This is useful enough for me to use again."**

This is much closer to the actual product goal.

#### 2. KPI Tree

<img width="440" height="472" alt="Screenshot 2026-09-11 115802" src="https://github.com/user-attachments/assets/2bec2513-e016-4862-9b48-3cd7944ba997" />

#### 3. Metric Layer 1 - Discovery & Activation

**Question:**

**Are students finding and trying Voice?**

| Metric                          | Definition                                                                           | Why track it                       |
| ------------------------------- | ------------------------------------------------------------------------------------ | ---------------------------------- |
| **Voice Study discovery rate**  | % of target users exposed to the Voice Study entry point who notice/interact with it | Measures discoverability           |
| **Voice activation rate**       | % who start their first Voice learning session                                       | Measures initial adoption          |
| **Time to first Voice session** | Time from seeing the feature to starting Voice                                       | Identifies friction                |
| **First-session completion**    | % completing a meaningful Voice interaction                                          | Distinguishes curiosity from value |

**Primary activation metric**

**% of eligible students completing their first meaningful Voice learning session within 7 days of exposure.**

This is better than simply measuring:

"How many people clicked the microphone?"

#### 4. Metric Layer 2 - Voice Experience Quality

This is critical because our research identified **trust and accuracy** as major barriers.

**Track:**

🎙️ **Speech recognition success rate**

% of Voice interactions where the user doesn't need to repeat or correct their input.

🔄 **Recovery rate**

% of misunderstood inputs that are successfully recovered through clarification.

❌ **Voice abandonment rate**

% of users who start Voice but leave after the first interaction.

⌨️ **Voice → Text switch rate**

This is **not automatically a bad metric.**

If students switch to text because they're in a library, that's a legitimate use case.

Instead, investigate:

**Why did they switch?**

Possible reasons:

- Privacy
- Recognition error
- Need to type something precise
- Preference
- Technical issue

**User-reported trust**

After a session:

**"How confident were you that ChatGPT understood what you said?"**

Measure on a 1-5 scale.

#### 5. Metric Layer 3 - Learning Value

This is what separates our product from a generic Voice feature.

Study Mode is explicitly designed around understanding rather than simply receiving an answer, including guided questioning, explanations and knowledge checks.

**Key metrics**

**Learning session completion**

% of Voice learning sessions that reach a meaningful learning outcome.

**Quiz completion**

% of students who complete a quiz/practice activity after the Voice interaction.

**Knowledge improvement**

For selected experiments:

Post-session quiz score − pre-session quiz score

**Task success**

Ask:

"Did Voice help you understand what you were trying to learn?"

**Perceived learning**

% responding "Yes, I understand this better now."

#### 6. Metric Layer 4 - Retention & Habit

This is arguably the **most important layer.**

**D1 / D7 / D30 Voice retention**

Percentage of first-time Voice learning users who return.

I'd especially focus on:

**7-day repeat Voice usage**

% of first-time Voice learning users who complete another meaningful Voice learning session within 7 days.

And:

**30-day Voice learning retention**

% returning to Voice learning within 30 days.

**Voice frequency**

Average:

**Meaningful Voice learning sessions / active student / week**

This tells us whether we're creating occasional experimentation or genuine behavior change.

#### 7. Business / Product Outcome Metrics

Ultimately, Voice adoption should improve the broader ChatGPT experience.

Track:

**Overall engagement**

- Sessions per student
- Weekly active users
- Learning sessions per week

**Retention**

Compare:

Students who adopt Voice

vs.

Similar students who don't adopt Voice

on:

- 7-day retention
- 30-day retention
- Weekly usage

**Cross-feature engagement**

Do Voice users subsequently use:

- Study Mode
- File uploads
- Quizzes
- Image input
- Follow-up conversations

more frequently?

#### 8. Guardrail Metrics 🚨

We shouldn't increase Voice usage at the expense of experience quality.

Track:

**Technical**

- Voice crash rate
- Latency
- Session failure rate
- Microphone permission failure
- Speech recognition errors

**User experience**

- Negative feedback rate
- Conversation abandonment
- "Not understood" reports
- User complaints about privacy
- Accidental Voice activation

**Cost / operational**

- Average Voice session duration
- Compute/inference cost per active Voice learner
- Cost per successful learning session

#### 9. Segment the metrics

Because our problem is specifically about India, don't look only at aggregate Voice adoption.

Break metrics down by:

| Dimension            | Example                                                 |
| -------------------- | ------------------------------------------------------- |
| **Language**         | English / Hindi / Hinglish / Tamil / Telugu etc.        |
| **Age**              | 18–20 / 21–24                                           |
| **OS**               | Android / iOS                                           |
| **New vs existing**  | New ChatGPT users / existing users                      |
| **Network**          | Good / poor connectivity                                |
| **Location type**    | Urban / non-urban                                       |
| **Study task**       | Concept learning / quiz / interview / language practice |
| **Voice experience** | First-time / repeat user                                |

This is especially important because the original problem includes **language and context**, not just feature discoverability.

#### 10. My recommended dashboard

I would keep the executive dashboard to **8 metrics:**

| Type             | Metric                                 | Goal               |
| ---------------- | -------------------------------------- | ------------------ |
| ⭐ **North Star** | **Weekly Repeat Voice Learning Users** | Overall success    |
| Activation       | First meaningful Voice session         | Get users started  |
| Activation       | Voice activation rate                  | Measure adoption   |
| Quality          | Voice session success rate             | Ensure Voice works |
| Trust            | Speech-understanding confidence        | Reduce anxiety     |
| Value            | Learning task completion               | Prove usefulness   |
| Retention        | 7-day Voice repeat rate                | Build habit        |
| Guardrail        | Voice abandonment/error rate           | Protect UX         |

#### 11. Example target for an MVP experiment

For illustration-not a claim about current ChatGPT performance-I would set an experiment target such as:

**+20% relative increase in 7-day repeat Voice learning usage among exposed Indian students, with no deterioration in Voice error/abandonment rates.**

The experiment would compare:

**Control**

Existing ChatGPT Voice / Study Mode experience

vs.

**Treatment**

**Voice-first Learning Coach**

Then measure:

**Activation → Successful session → Repeat → Learning outcome**

#### 12. The most important metric distinction

❌ **Vanity metric**

**Number of Voice sessions**

A user could start Voice, say one sentence, encounter an error and leave.

**Better metric**

**Successful Voice learning sessions**

The user actually achieved something.

**Best metric for our product**

**Weekly Repeat Voice Learning Users**

The user achieved value **and chose to come back.**

That's the behavior change we're trying to create.

**Final measurement framework**

**Discovery:** Can students find Voice?

↓

**Activation:** Do they try it?

↓

**Quality:** Does Voice understand them?

↓

**Value:** Does Voice actually help them learn?

↓

**Retention:** Do they return?

↓

**North Star:** Do students repeatedly choose Voice for learning?

🎯 **North Star**

**Weekly Repeat Voice Learning Users**

**Product success statement**

**“We have succeeded when Indian students don't merely try Voice-they repeatedly choose it because conversational learning is more useful and natural than typing.”**

This measurement approach also avoids optimizing for a single feature click and instead connects the feature to **customer value and repeat behavior**, which is the purpose of a strong North Star framework.
