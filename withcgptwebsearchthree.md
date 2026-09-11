## Milestone 3 - Voice-first Learning Coach for Indian Students

### Solution to Designing and Building a Prototype: Voice-first Learning Coach for Indian Students

#### Task 3 - Lay out the user flow - how will a user discover and use voice now?

**User Flow: Voice-first Learning Coach**

For our chosen segment-Indian students using ChatGPT mobile-I would redesign the journey around one principle:

**Don't make users discover “Voice.” Make them discover a useful reason to use Voice.**

ChatGPT already supports Voice conversations and Study Mode, including interactive, step-by-step learning.

**End-to-end user flow**

                    DISCOVERY
                        │
                        ▼
              ┌─────────────────┐
              │  Student opens  │
              │    ChatGPT      │
              └────────┬────────┘
                       │
                       ▼
             ┌─────────────────────┐
             │ "What do you want   │
             │  to do today?"      │
             └─────────┬───────────┘
                       │
            ┌──────────┴───────────┐
            ▼                      ▼
       Type a question        🎙️ Study with Voice
                                   │
                                   ▼
                         ┌──────────────────┐
                         │ "What are you   │
                         │  studying?"     │
                         └────────┬─────────┘
                                  │
                                  ▼
                         User speaks naturally
                         English / Hindi /
                         Hinglish
                                  │
                                  ▼
                       ┌────────────────────┐
                       │ ChatGPT understands│
                       │ + responds         │
                       └─────────┬──────────┘
                                 │
                                 ▼
                       ┌────────────────────┐
                       │ Explain → Ask →    │
                       │ Listen → Adapt     │
                       └─────────┬──────────┘
                                 │
                       ┌─────────┴─────────┐
                       ▼                   ▼
                Continue Voice        Switch to Text
                       │                   │
                       └─────────┬─────────┘
                                 ▼
                         Learning completed
                                 │
                                 ▼
                       "Want to practice?"
                                 │
                                 ▼
                          Quiz / Practice
                                 │
                                 ▼
                       Progress / next task

#### 1. Discovery: Give Voice a job to do

**Current mental model**

The user sees:

🎙️ microphone

and thinks:

**"That's voice input."**

That's not enough to change behavior.

**Proposed experience**

Instead, surface a contextual prompt:

🎙️ **Study with Voice**

Talk through your doubts instead of typing them.

Possible entry points:

- Study Mode
- Home screen
- Student-related prompts
- After repeated typed learning queries
- When the user is typing several follow-up questions

The goal is to communicate:

**Voice = learning interaction**

rather than:

**Voice = alternative keyboard**

#### 2. First-time activation

Student taps:

🎙️ **Study with Voice**

Instead of immediately recording, ChatGPT explains the benefit:

**"Talk naturally. I'll ask questions, explain concepts, and help you practice."**

Then:

**[Start Voice]**

This reduces uncertainty about what will happen.

OpenAI's Voice experience already supports natural back-and-forth conversations, while Study Mode is designed to guide users through concepts using questions and iterative learning.

#### 3. User speaks naturally

Student:

**"I have an exam tomorrow and I don't understand probability."**

Important:

**Don't require the user to formulate a perfect prompt.**

The system should interpret the intent and take over the structure.

ChatGPT:

**"No problem. Let's start with the basics. Before I explain probability, what do you already know about it?"**

This changes the interaction from:

**User drives everything**

to:

**User + AI collaborate.**

#### 4. Conversational learning loop

The core loop becomes:

🎙️ **Speak**

↓

🧠 **Understand**

↓

💬 **Explain**

↓

❓ **Ask**

↓

🎙️ **Listen**

↓

🧠 **Evaluate**

↓

🎯 **Adapt**

For example:

**ChatGPT:**
"What's the difference between independent and dependent events?"

**Student:**
"Independent means one event doesn't affect the other."

**ChatGPT:**
"Exactly. Let's test that with an example..."

This is where Voice becomes **meaningfully different from typing.**

#### 5. Handle Indian language naturally

The student shouldn't have to think:

"Should I use English?"

They can say:

**"Explain this thoda simple way mein."**

or:

**"Hindi mein samjhao, but technical terms English mein rakho."**

The product should preserve the user's chosen language style across the conversation.

#### 6. Handle uncertainty instead of failing silently

Suppose Voice isn't sure what the student said.

**Current-feeling experience**

Misunderstanding → wrong response → user gets frustrated.

**Proposed experience**

**"I may have misheard one part. Did you say Bayes' theorem?"**

**[Yes] [Correct]**

This is important because it builds:

**Trust → recovery → continued conversation**

rather than:

**Error → abandonment**

#### 7. Give the user control

At any point:

🎙️ **Voice**

or

⌨️ **Type**

The conversation continues seamlessly.

For example:

Student is in a hostel:

🎙️ "Explain..."

Roommate enters.

Student taps:

⌨️ **Continue by typing**

The conversation doesn't restart.

ChatGPT's current Voice experience already supports switching between Voice and typing, providing a foundation for this interaction.

#### 8. Multimodal learning

This is especially important for students.

Student uploads:

📄 PDF
📸 Screenshot
📝 Question paper

Then says:

**"Explain question 4 to me."**

ChatGPT:

"Sure. Let's look at question 4. First, what do you think the answer might be?"

Now Voice isn't competing with multimodal ChatGPT.

It's **the conversational layer on top of it.**

#### 9. End with a learning action

Don't simply end:

**"Anything else?"**

Instead:

**You've understood the basics. What next?**

🎯 **Take a 5-question quiz**

🔄 **Explain another example**

🗣️ **Practice explaining it yourself**

📚 **Continue this chapter**

This creates a natural next action.

#### 10. Create the habit loop

After several successful sessions:

Need to learn something
        ↓
Open ChatGPT
        ↓
"Study with Voice"
        ↓
Talk naturally
        ↓
Get personalized explanation
        ↓
Practice
        ↓
Feel progress
        ↓
Return next time

The key behavioral change is:

**Before**

**"I need to type something into ChatGPT."**

**After**

**"I'll talk to ChatGPT about this."**

**Current vs Proposed User Flow**

| Stage          | Current experience        | Proposed experience                       |
| -------------- | ------------------------- | ----------------------------------------- |
| **Discovery**  | See microphone            | See **Study with Voice**                  |
| **Motivation** | "Input by voice"          | "Learn through conversation"              |
| **Starting**   | Start speaking            | AI explains what it can do                |
| **Prompting**  | User formulates question  | User speaks naturally                     |
| **Learning**   | Ask → answer              | **Explain → ask → listen → adapt**        |
| **Language**   | User may adapt speech     | Natural multilingual/code-switched speech |
| **Error**      | Repeat/restart            | AI asks for clarification                 |
| **Privacy**    | Voice or nothing          | Seamless Voice ↔ Text                     |
| **Materials**  | Voice separate from files | Voice + PDF/image/context                 |
| **End**        | Conversation ends         | Quiz/practice/next learning action        |
| **Habit**      | Occasional Voice          | **Repeat Voice learning sessions**        |

🎯 **The "Aha" moment**

The most important moment in the flow is:

**Student realizes they don't have to formulate a perfect prompt.**

They can simply say:

"I don't understand this."

And ChatGPT takes responsibility for guiding the conversation.

That's the point where Voice changes from an **input feature** into an **interaction model.**

**Final user journey**

**Discover**

🎙️ Study with Voice

↓

**Try**

"I don't understand this concept."

↓

**Trust**

ChatGPT understands natural speech / asks for clarification

↓

**Experience value**

Conversational tutoring

↓

**Control**

Voice ↔ Text whenever needed

↓

**Learn**

Explain → Practice → Quiz

↓

**Habit**

**"Next time, I'll just talk to ChatGPT."**

**Product principle**

**Make Voice discoverable through its value, not through its existence.**

That is the core UX change I'd propose for the MVP.
