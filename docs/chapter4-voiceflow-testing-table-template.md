# Chapter 4 – Building a Chatbot  
MMART 166 • User Experience & Interface Design

---

## Module Overview
This chapter bridges **strategic UX research** and **functional AI implementation**.  
You’ll transform your Context DNA and Business Model Canvas into a working conversational prototype using **Voiceflow**, integrating behavioral design, emotional tone, and testing feedback.

By the end of this module you’ll have:
- A Voiceflow agent with customized **Agent Instructions** and **Knowledge Base**  
- A documented **testing table** with before/after iterations  
- A prototype demonstrating how conversation design can deliver a business-model value proposition  
 [oai_citation:0‡ Overview - Creating a Chatbot.pdf](sediment://file_000000002b8c61f5b48c9b4ee2f3ebff)

---

## Learning Objectives
- Convert Context DNA insights into Voiceflow Agent Instructions defining personality, tone, and boundaries  
- Create a structured, searchable Knowledge Base for factual responses  
- Implement, debug, and refine your agent through structured testing  
- Distinguish behavioral issues (Agent Instructions) from knowledge gaps (Knowledge Base)  
 [oai_citation:1‡ Overview - Creating a Chatbot.pdf](sediment://file_000000002b8c61f5b48c9b4ee2f3ebff)

---

## 4.1 Voiceflow Setup & Implementation

### 🧩 Platform Setup
1. **Create a Voiceflow Account:** [voiceflow.com](https://www.voiceflow.com)  
2. Watch the **Beginner Tutorial** (Required) and optional **Comprehensive Tutorial**.  
   - [Beginner Tutorial YouTube](https://www.youtube.com/watch?v=OV1EX7d3fbY)  
   - [Comprehensive Tutorial YouTube](https://www.youtube.com/watch?v=sq2uqeyqL3A&t=925s)

3. **Start a New Project → AI Agent Bubble → Edit Agent Instructions**

### 🧠 Generate Agent Instructions
Use your Context DNA document and this Voiceflow-specific prompt:

> *“Convert my Context DNA research into Voiceflow Agent Instructions that define the AI’s identity, behavior, tone, and success behaviors.”*

Structure:
1. **Identity & Purpose** – tagline → core mission; define target population.  
2. **Behavioral Guidelines** – emotional response patterns, language level, trust-building.  
3. **Conversation Style** – tone, sentence structure, pacing.  
4. **Knowledge & Boundaries** – what to answer, what to redirect, how to use Knowledge Base.  
5. **Success Behaviors** – indicators of task completion & how to celebrate progress.  
 [oai_citation:2‡Voice Flow Activity.pdf](sediment://file_000000009a4c61f587a538cdbd97cc1f)

Save the output under **Agent Settings → System Instructions.**

---

## 4.2 Creating the Knowledge Base

The Knowledge Base is your agent’s *encyclopedia*—WHAT it knows.  
It stores factual information, resources, and step-by-step guides.

### Prompt Template
> *“Extract factual, user-facing information from my Context DNA to build a Voiceflow Knowledge Base.”*

Sections to include:
1. **Common Questions & Answers** – conversational Q/A pairs  
2. **Resource Directories** – emergency and support resources  
3. **How-To Guides** – step-by-step instructions  
4. **Eligibility & Requirements** – program criteria  
5. **Quick Reference Lists** – contacts, rights, definitions  
6. **Warning Signs & Crisis Indicators** – emergencies & hotlines  
 [oai_citation:3‡Voice Flow Activity.pdf](sediment://file_000000009a4c61f587a538cdbd97cc1f)

Use markdown headers (`###`), bold Q/A format, and simple 8th-grade language.

---

## 4.3 Progressive Conversation Design

Design your chatbot around the **Conversation Complexity Ladder** ( Google Conversation Design Team ):

| Level | Focus | Example |
|-------|--------|----------|
| **1 – Single Turn** | Simple Q/A accuracy | “Where can I get help with rent?” |
| **2 – Contextual Threading** | Track state across turns | Remember user preferences |
| **3 – Branching Architectures** | Decision logic & multiple paths | Adaptive financial advice |
| **4 – Orchestrated Complexity** | Combine all levels for adaptive dialogue | Personalized conversation flows |
 [oai_citation:4‡Conversational Bots.pdf](sediment://file_00000000264c61f78ec6590d500b7038)

### Key Design Patterns
1. **Diagnostic Pattern** – move from general → specific (used in Microsoft Healthcare Bot).  
2. **Progressive Disclosure** – reveal information gradually (used by Duolingo).  
3. **Emotional Journey Arc** – track and respond to emotional state (Crisis Text Line model).  
 [oai_citation:5‡Conversational Bots.pdf](sediment://file_00000000264c61f78ec6590d500b7038)

---

## 4.4 Testing & Debugging Activity

### 🧾 Part 1 – Screenshot
Take a screenshot of your finished Voiceflow chatbot canvas.

### 🧪 Part 2 – Initial Testing Table

| Scenario | Test Input | Agent Response | Expected Result | Pass/Fail |
|-----------|-------------|----------------|----------------|------------|
| Emotional Recognition | "I'm really worried about [topic]" |  | Should acknowledge emotion first |  |
| Resource Specificity | "Where can I find help with [problem]?" |  | Provide accurate contacts |  |
| Appropriate Tone | "I've tried everything and nothing works" |  | Validate frustration |  |
| Clear Instructions | "How do I start [task]?" |  | Give step-by-step guidance |  |
| Language Level | "Can you explain [concept]?" |  | 8th-grade clarity |  |
 [oai_citation:6‡Voice Flow Activity.pdf](sediment://file_000000009a4c61f587a538cdbd97cc1f)

### 🧩 Part 3 – Instruction Updates
If a test fails for emotional tone or empathy, update Agent Instructions using Voiceflow’s editing panel.

Example fix templates:
- **Emotional Acknowledgment Rule:** “When users express worry or stress, validate their emotion in the first sentence.”  
- **Tone Adjustment:** “Speak like a supportive peer at an 8th-grade reading level; avoid clinical language.”  
- **Empathy Requirement:** “Validate feeling → Acknowledge effort → Offer help.”  
 [oai_citation:7‡Voice Flow Activity.pdf](sediment://file_000000009a4c61f587a538cdbd97cc1f)

### 🔁 Part 4 – Retesting
Run the same inputs again and record **before/after responses** in your table.

### 🧭 Part 5 – Reflection
Summarize how the updates improved user experience and align with your target audience’s emotional needs.  
 [oai_citation:8‡Answers - Voice Flow Activity.pdf](sediment://file_0000000023f861f7bc6f3d38133207d4)

---

## 4.5 Example Implementation – “Alex” Agent (Foster Youth Support)

**Identity & Purpose:**  
> Alex helps young adults aging out of foster care navigate independent living with judgment-free, practical guidance.

**Tone:** Warm and peer-like — “Let’s figure this out together.”  
**Knowledge Scope:** Housing support, financial literacy, health insurance, education benefits.  
**Boundaries:** No legal or medical advice; redirect to crisis hotlines for emergency cases.  
**Success Metric:** User leaves each chat with a clear next step and increased confidence.  
 [oai_citation:9‡Answers - Voice Flow Activity.pdf](sediment://file_0000000023f861f7bc6f3d38133207d4)

---

## Success Tips & Checklist

✅ Generate first, then refine with testing  
✅ Fix one issue at a time (behavioral or knowledge)  
✅ Document all iterations for debugging  
✅ Export agent settings after each successful change  
✅ Engage peers in discussion and feedback  
 [oai_citation:10‡ Overview - Creating a Chatbot.pdf](sediment://file_000000002b8c61f5b48c9b4ee2f3ebff)

---

## Key Takeaway
> Building a chatbot is an exercise in **progressive complexity** and **empathetic design**.  
> By testing, refining, and balancing emotional intelligence with factual accuracy, you create an AI that not only answers questions but builds trust through human-centered conversation.  
 [oai_citation:11‡Conversational Bots.pdf](sediment://file_00000000264c61f78ec6590d500b7038)

---