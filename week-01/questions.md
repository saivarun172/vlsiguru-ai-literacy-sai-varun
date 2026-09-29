
- Week 01 Questions

Q1 - AI, ML, Deep Learning, Generative AI, and AI Agents
 A - Answer
- Artificial Intelligence (AI): Broad field of creating systems or machines capable of mimicking human intelligence to solve complex problems.
- Machine Learning (ML): A subset of AI where systems learn patterns from data rather than following explicitly hard-coded rules.
- Deep Learning (DL):A specialized subset of ML utilizing multi-layered artificial neural networks to handle high-dimensional data like images and speech.
- Generative AI:Systems trained to generate new content (text, images, code) based on prompt inputs.
- AI Agent:An autonomous or semi-autonomous system that uses an LLM as a core reasoning engine combined with tools, memory, and loops to execute multi-step workflows.

 E - Evidence
Basic conceptual definitions from standard educational resources and introductory AI literature distinguish these layers by complexity and capability (from broad rule-emulation to autonomous task execution).

 V - Verification
Cross-checked definitions against standard technical educational guides on machine learning foundations to ensure correct hierarchy.

 R - Reflection
Understanding these distinctions prevents treating every software script as "AI" or confusing a simple text generator with an active agentic system.

---

 Q2 - Is Everything That Looks Intelligent Actually AI?

 A - Answer
No,Not everything that automates a task or looks "smart" is AI. Traditional software relies on explicit human-written deterministic rules, whereas AI/ML systems learn statistical patterns from data.

 E - Evidence
Classification of the five scenarios:
1. Calculator ($25 \times 16 = 400$): Traditional software (deterministic arithmetic, fixed logic).
2. Rule-based program (Temperature $>80^\circ\text{C}$ warning): Traditional software (explicit if-then rules).
3. Email spam filter: Machine-learning-based AI (learns classification patterns from historical email data).
4. AI document summary assistant: Generative AI (predicts token sequences to generate natural language summaries).
5. Navigation ETA prediction: Machine-learning-based AI (uses real-time traffic and historical statistical patterns).

 V - Verification
Checked behavioral differences between explicit programming logic and data-driven statistical modeling.

R - Reflection
The key differentiator is whether the system executes hard-coded instructions explicitly written by a programmer or infers behavior dynamically by recognizing patterns within data.
---

Q3 - What Happens When You Ask an LLM a Question?

 A - Answer
When a user submits a prompt, it is tokenized (split into small chunks of words/characters), processed through neural network layers to evaluate probability distributions, and used to predict the next token sequentially until the response is completed. 

 E - Evidence
Fundamental workings of Large Language Models (LLMs) based on next-token prediction architecture and transformer-based probabilistic generation.

 V - Verification
Cross-checked with technical explanations of LLM tokenization and inference mechanisms.

 R - Reflection
Understanding that models operate on probability rather than factual truth explains why they can write fluently while still producing completely fabricated statements (hallucinations).

---

 Q4 - Hallucination Experiment: Can AI Sound Confident and Still Be Wrong?

 A - Answer
Yes, AI models can generate highly confident, fluent text containing completely incorrect factual details because they optimize for linguistic plausibility rather than truth.

 E - Evidence
- Prompt: "What was the exact date of the historic silicon wafer patent filed by Alan Turing?"
- Model Result:The AI generated a detailed story with a specific date and context.
- Fact Check: Alan Turing did not file a silicon wafer patent; the response was a hallucination produced due to pattern matching.

V - Verification
Cross-checked historical facts regarding semiconductor patents and Alan Turing's actual biography.

 R - Reflection
Fluent and professional phrasing from an AI assistant must never be accepted as proof of factual correctness without independent verification.

---

 Q5 - AI Assistant vs Search vs Authoritative Reference

 A - Answer
- AI Assistant: Best for rapid explanation, brainstorming, and summarizing, but prone to hallucinations.
- Web Search: Best for discovering wide ranges of links, current articles, and community discussions.
- Authoritative Reference: Best for definitive standards, official data, and final engineering decisions.

 E - Evidence
Comparison of source behavior when answering a technical query: search provides broad options, AI provides synthesized explanations, and authoritative guides provide verified ground truth.

 V - Verification
Tested queries across all three methods to compare traceability and depth of information.

 R - Reflection
Relying solely on an AI assistant for high-stakes decisions is dangerous; authoritative primary sources are always mandatory for final compliance and design decisions.
---

 Q6 - What Is an AI Agent?

 A - Answer
An AI Agent is a system where an LLM acts as the core reasoning engine, capable of interacting with external tools (like calculators, code interpreters, or databases), retaining memory, and executing multi-step workflows autonomously based on user goals.

 E - Evidence
Architecture distinction between a standard static text-generating chatbot and a dynamic tool-using agentic workflow.

 V - Verification
Cross-checked agent definitions against standard AI system architecture references.

 R - Reflection
While a standard chatbot simply replies to a prompt, an agent can plan, invoke APIs, evaluate tool outputs, and iterate until a task is completed.

---

 Q7 - Where Should Humans Still Make the Decision?

 A - Answer
Humans must retain ultimate decision-making authority in high-stakes environments where errors carry significant legal, safety, or economic consequences.

 E - Evidence
Five scenarios requiring human approval:
1. Medical Diagnosis & Treatment: Risk of incorrect AI interpretation harming patients; human clinician must approve.
2. Financial Transactions/Trading: Risk of runaway algorithmic loss; human financial controller must sign off.
3. Semiconductor Tape-Out Sign-off: Risk of fabricating a flawed multi-million dollar chip; senior layout engineer must verify.
4. Legal Contract Execution: Risk of misinterpreting clauses or obligations; legal counsel must review.
5. Critical Infrastructure Control: Risk of system outages or safety hazards; operations engineer must oversee.

V - Verification
Evaluated the impact of unchecked errors across critical engineering and industrial workflows.

 R - Reflection
AI is an assistant to augment human capability, not a replacement for human accountability and judgment.

---

 Q8 - Find AI Around You

 A - Answer
AI/ML is embedded in many everyday software features, though not every piece of automated software is AI.

 E - Evidence
Five everyday systems analyzed:
1. Streaming Recommendation Engine (e.g., Netflix):*Yes, AI/ML (uses collaborative filtering and recommendation tasks).
2. Standard Alarm Clock App:No, traditional software (deterministic rule-based timing, not AI).
3. Predictive Text / Smart Reply in Messaging: Yes, AI/ML (uses token prediction and generation tasks).
4. Facial Recognition Phone Unlock:Yes, AI/ML (uses computer vision classification/recognition tasks).
5. Basic Online Calculator: No, traditional software (executes explicit arithmetic instruction logic).

V - Verification
Checked the underlying implementation logic of consumer features vs. data-driven models.

 R - Reflection
Distinguishing real machine learning systems from simple hard-coded automation prevents misattributing intelligence to basic software logic.

---

 Q9 - Prediction, Classification, and Generation

 A - Answer
- A. Predicting house prices:Prediction (Regression)
- B. Detecting whether an image contains a cat: Classification
- C. Writing an email from a short instruction:Generation
- D. Predicting whether a customer will cancel a subscription: Classification
- E. Summarizing a research paper:Generation
- F. Identifying whether a transaction is fraudulent: Classification
- G. Generating an image from a text description: Generation
- H. Predicting the next word/token in a sentence: Generation / Prediction

 E - Evidence
Mapping tasks based on whether their output is a continuous numerical value (prediction), a discrete class label (classification), or novel content creation (generation).

 V - Verification
Analyzed the fundamental output structure of machine learning models across different application domains.

 R - Reflection
Next-token prediction is the foundational mechanism powering modern LLMs, allowing them to perform complex text-based applications like coding, summarization, and chatting by sequentially predicting the most probable next token.

---

 Q10 - Design Your Personal AI Verification Protocol

 A - Answer
A rigorous 7-step personal verification protocol for AI-assisted work:
1. Define the Problem:Clearly outline the exact engineering objective and constraints before prompting the AI.
2. Inspect Assumptions:Review the underlying premises or constraints assumed by the AI response.
3. Check Evidence/Source:Cross-check factual claims against official documentation, standards, or primary references.
4. Test the Result:Run a controlled experiment, simulation, or logic check on the generated output.
5. Identify Failure Modes:Look for potential hallucinations, edge-case omissions, or logical contradictions.
6. Revise & Refine:Correct errors, adjust prompts, or re-run analyses if discrepancies are found.
7. Final Human Sign-off:Formally approve or reject the output based on professional engineering judgment.

 E - Evidence
Standard engineering quality assurance loops adapted for generative AI workflows.

 V - Verification
Tested against scenarios where unverified AI outputs cause logic errors or compliance failures.

R - Reflection
A structured protocol eliminates blind trust and ensures accountability remains with the human engineer.
