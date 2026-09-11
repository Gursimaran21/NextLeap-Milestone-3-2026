## Milestone 3 - Voice-first Learning Coach for Indian Students

### Solution to Designing and Building a Prototype: Voice-first Learning Coach for Indian Students

#### Task 5 - Define success metrics for the feature and outline what you would track.

**3-Page Product Document**

**Project: Voice-first Learning Coach for Indian Students**

**One-line description**

**A Voice-first learning experience that helps Indian students learn through natural conversation, making Voice more useful, trustworthy, and repeatable than simply using it as a speech-to-text input.**

**PAGE 1 - WHY ARE WE BUILDING THIS?**

Your first page should answer:

**What problem are we solving, for whom, and why does it matter?**

**1. Header**

**Project Name:** Voice-first Learning Coach

**Team:** Product / Design / Engineering / Research

**Contributors:** Your name + relevant contributors

**Status:** In Review

**Launching on:** TBD - MVP experiment

**Resources:** Link to research, survey, interview notes, wireframes, etc.

**2. Problem Definition**

Keep this to **4-5 sentences**, because the template specifically asks for a concise problem definition.

**Recommended version**

**Indian students are among the heaviest ChatGPT users in India, with this peer group generating just under half of all ChatGPT messages in the country. However, many students continue to rely primarily on typing even when Voice could make learning more conversational and efficient. User research indicates that uncertainty around speech recognition, privacy in shared environments, lack of control, and unclear Voice-specific value can prevent students from adopting Voice regularly. This creates an opportunity to make Voice a trusted learning interaction rather than simply an alternative way to enter prompts. Solving this could increase repeat Voice usage while helping students engage more naturally and actively with ChatGPT for learning.**

**Why this is strong**

It answers all five questions from your manager's template:

| Manager asks         | Your answer                                              |
| -------------------- | -------------------------------------------------------- |
| What is the problem? | Low/repeat Voice adoption                                |
| Who?                 | Indian students 18–24                                    |
| Business value?      | Increased engagement/repeat Voice usage                  |
| User benefit?        | More natural, conversational learning                    |
| Why now?             | India has a very large student + young ChatGPT user base |

**3. Goals**

Don't list 10 goals. Give your manager **3 prioritized goals.**

**P0 - Increase meaningful Voice adoption**

Increase the number of students who complete and repeat Voice-based learning sessions.

**P1 - Improve Voice trust**

Reduce abandonment caused by speech recognition uncertainty and lack of user control.

**P1 - Create differentiated Voice value**

Make Voice particularly useful for conversational learning through tutoring, questioning, practice and feedback.

**Metrics**

| Goal             | Metric                                                 |
| ---------------- | ------------------------------------------------------ |
| Adoption         | Voice activation rate                                  |
| Successful usage | Meaningful Voice learning session completion           |
| Retention        | **7-day repeat Voice learning rate**                   |
| Trust            | Speech-understanding confidence                        |
| Learning value   | Learning-task completion / knowledge-check improvement |

**North Star**

**Weekly Repeat Voice Learning Users**

This is important because a **Voice click isn't adoption.** Repeated use demonstrates that the experience has delivered enough value for the student to return.

**4. Non-Goals**

This section is important because it demonstrates product judgment and scope control.

Your template explicitly asks you to define what you aren't addressing.

**V1 Non-Goals**

❌ Rebuilding ChatGPT's underlying Voice/ASR technology

❌ Solving every regional-language Voice problem in India

❌ Building a complete education/LMS platform

❌ Replacing teachers or formal educational institutions

❌ Building a separate Voice app

❌ Optimizing Voice for every user segment

❌ Solving all privacy concerns around speaking in public spaces

**Scope**

**Focus exclusively on improving Voice adoption and repeat usage among Indian students for learning-related use cases.**

**PAGE 2 - WHY DO WE BELIEVE THIS IS A REAL PROBLEM?**

Your second page should contain your **evidence.**

Your template explicitly asks for user research/data, anecdotes, and competitive insights.

**5. Validation of the Problem**

Use a **three-column evidence structure.**

**Quantitative**

**OpenAI India data**

Gen Z users currently generate **just under half of all ChatGPT messages in India.** Young adults generate about 80%.

**India learning opportunity**

India has the **largest student population on ChatGPT globally**, with millions using ChatGPT for homework, exam preparation and exploring ideas.

**Qualitative**

Use your 5-6 interview insights here.

For example:

**"I don't want people around me hearing my questions."**

**"Typing feels more serious when I'm studying."**

**"If Voice misunderstands me, typing is easier."**

**"I don't know what Voice is actually better for."**

**Important:** If these came from your own interviews, label them **"User interviews — n=6"** rather than presenting them as OpenAI research.

**Product evidence**

ChatGPT already has the underlying capabilities needed for this direction:

- Study Mode
- Voice
- Step-by-step learning
- Socratic questioning
- Knowledge checks
- PDF/image study materials

OpenAI's current Study Mode explicitly supports voice dictation/conversations when available.

**6. Turn the research into a simple insight graphic**

I recommend putting this in the middle of Page 2:

<img width="460" height="575" alt="Screenshot 2026-09-11 125934" src="https://github.com/user-attachments/assets/e062c1f9-ccb5-481b-80e5-f4c63601ab9f" />

Then put the key insight underneath:

**Core insight: Students aren't necessarily rejecting Voice; they don't yet see enough value and trust to change their existing typing behavior.**

**7. Understanding the Target Audience**

**Segment**

**Indian students who use ChatGPT on mobile for learning but primarily type.**

This is a particularly strong segment because the cohort sends just under half of India's ChatGPT messages.

**Key personas**

You don't need 5 personas.

Use **3 lightweight personas:**

| Persona              | Need                               | Voice barrier               |
| -------------------- | ---------------------------------- | --------------------------- |
| **Exam Prepper**     | Understand/revise concepts quickly | Accuracy + control          |
| **Concept Explorer** | Ask follow-up questions            | Doesn't see Voice advantage |
| **Language Learner** | Practice speaking                  | Accent/language confidence  |

**8. Current User Journey**

Show this visually:

Student has a doubt

        ↓
        
Opens ChatGPT

        ↓
        
Formulates prompt

        ↓
        
Types

        ↓
        
Reads answer

        ↓
        
Types follow-up

        ↓
        
Repeats

Then:

**Pain points**

**Formulating prompts**

→ Cognitive effort

**Typing multiple follow-ups**

→ Slow

**Voice**

→ Available, but uncertain

**Shared environments**

→ Social/privacy barrier

**PAGE 3 - WHAT ARE WE BUILDING?**

This is the most important page.

Your template specifically asks for **Solution + User Flow/Wireframes + Key Features + Key Logic**, followed by launch readiness and open decisions.

**9. Solution**
    
**Voice-first Learning Coach**

**One-line solution**

**Transform Voice from a speech-input feature into a conversational learning experience where students can speak naturally, receive guided explanations, practice concepts, and switch seamlessly between Voice and text.**

OpenAI's existing Study Mode already supports Socratic questioning, step-by-step explanations, knowledge checks, and study materials, making it a natural foundation for this concept rather than requiring a completely separate learning product.

**10. Proposed User Flow**

Put your annotated wireframe here.

**Flow**

<img width="320" height="546" alt="Screenshot 2026-09-11 141838" src="https://github.com/user-attachments/assets/7e64c2ed-a8a9-4748-a3f0-aad1bd0086bb" />

**Critical UX principle**

**Don't ask users to discover Voice. Give them a reason to use Voice.**

This aligns well with OpenAI's current guidance that Voice can be useful when talking through a problem is easier than first creating a polished prompt.

**11. Key Features**

Keep this to **5 features maximum.**

**P0 - Study with Voice**

A contextual entry point into learning-focused Voice.

**P0 - Conversational Tutor**

**Explain → Ask → Listen → Adapt**

The AI guides rather than simply answers.

**P0 - Voice ↔ Text**

Students can switch modes without losing context.

**P1 - Language-flexible Voice**

Support natural English/Hindi/Hinglish interaction.

**P1 - Practice Loop**

End sessions with:

**Quiz / Practice / Continue learning**

**12. Key Logic**

Your manager's template asks about algorithm/schema/data changes.

Don't invent complicated backend architecture.

Write:

**Conversation state**

Maintain:

- Learning objective
- Student's knowledge level
- Current topic
- Misconceptions
- Questions already answered
- Preferred interaction mode

**Voice confidence**

If speech recognition confidence is low:

**Ask → Confirm → Continue**

instead of generating a potentially incorrect answer.

**Mode switching**

Maintain the same conversation context across:

**Voice ↔ Text**

**Learning state**

After each session, capture:

Topic → Progress → Knowledge gap → Recommended next action

**13. Launch Readiness**

Keep this practical.

| Phase    | Deliverable                     |
| -------- | ------------------------------- |
| Week 1   | Finalize UX + experiment design |
| Week 2   | Prototype                       |
| Week 3–4 | MVP development                 |
| Week 5   | Internal dogfooding             |
| Week 6   | QA + instrumentation            |
| Week 7   | Limited experiment              |
| Week 8   | Evaluate results                |

You can change these timelines based on your actual team.

**14. Experimentation Plan**

This should be very clear.

**A/B test**

**Control**

Existing ChatGPT Voice / Study Mode experience

**Treatment**

Voice-first Learning Coach

**Primary metric**

**7-day repeat Voice learning rate**

**Secondary metrics**

- Voice activation
- Successful Voice session
- Session completion
- Speech-understanding confidence
- Learning-task completion
- 30-day Voice retention

**Guardrails**

- Voice error rate
- Session abandonment
- Latency
- Negative feedback
- Cost/session

**15. Open Questions & Decisions**

This is where you show your manager that you understand **trade-offs.**

**Decisions already made**

✅ Target segment: Indian students 

✅ Primary solution: Voice-first Learning Coach

✅ North Star: Weekly Repeat Voice Learning Users

✅ MVP scope: Learning use cases

**Open questions**

**1. Should the first experience be inside Study Mode or a new entry point?**

**2. Should we launch English + Hinglish first or include regional languages?**

**3. How much Voice accuracy improvement is required before launch?**

**4. Should Voice sessions automatically switch to text in low-privacy contexts?**

**5. Should learning progress persist between Voice sessions?**

**Trade-offs**

**Scope vs coverage:** Start with students rather than solving Voice for all Indian users.

**Accuracy vs speed:** Use existing Voice infrastructure rather than rebuilding ASR.

**Feature breadth vs learning:** Focus MVP on 2–3 high-frequency learning jobs.

**Activation vs retention:** Optimize for repeat Voice usage rather than microphone clicks.
