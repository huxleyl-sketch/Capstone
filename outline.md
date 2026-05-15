Yes. Based on your current topic, I would structure the paper so the literature review does **not** try to prove your argument yet. Its job is to build the conceptual tools you need for the model section.

**Working Title**
Constraint, Information, and Knowability: Formal and Philosophical Limits of Artificial Intelligence

**Central Research Question**
How can constraint satisfaction, information theory, empiricism, and determinism be used to reason about the limits of artificial intelligence systems?

**Possible Thesis Direction**
AI systems can be analysed as structures that transform available information into generated outputs. Because these systems depend on data, computational representation, and tractable processing, their limits can be examined through constraint satisfaction, information theory, and theories of knowledge. This does not establish a single fixed limit for all AI, but it provides a framework for identifying where limits may arise.

**Abstract**
Purpose:
State what the paper investigates.

Include:
1. The problem: AI capabilities are expanding, but their limits remain conceptually unclear.
2. The approach: the paper combines CSPs, information theory, empiricism, and determinism.
3. The method: it develops a conceptual model of AI as `data -> processing -> generation`.
4. The contribution: it identifies limits related to information availability, representation, computability, and prediction.
5. The conclusion: AI limits should be discussed as conditional on model structure, available information, and computational constraints.

**Introduction**
1. Introduce AI as a contemporary problem
Explain that recent AI systems, especially large language models, have increased interest in the question of what AI can and cannot do.

2. Define the scope of the paper
Make clear that you are not evaluating one model, such as ChatGPT, but reasoning about AI systems at a structural level.

3. Introduce your working model
AI can be treated as a system involving:
`data/input -> processing/model structure -> generation/output`

4. Explain why this structure matters
This lets you connect AI to:
`CSPs`: formal constraints and solvability  
`Information theory`: information, uncertainty, and compression  
`Empiricism`: knowledge from experience/data  
`Determinism`: whether future states are knowable or predictable

5. State the research question
Use one clear question, not several competing ones.

6. Preview the paper
Briefly explain that the literature review defines the relevant concepts, the model section connects them, and the analysis section considers the implications.

**Literature Review Opening**
Purpose:
Explain that the literature review establishes the definitions and debates needed for the later model.

Do not argue your conclusion here yet. Instead, show what each field contributes and where tensions appear.

**1. Definitions of Artificial Intelligence**
Goal:
Show that AI has no single stable definition, which makes your working definition necessary.

Cover:
1. AI as imitation of human intelligence.
2. AI as rational action or problem-solving.
3. AI as prediction or function approximation.
4. AGI as a stronger and more contested concept.

Analytical focus:
Compare what each definition includes and excludes.

Key question:
Which definition is most useful for analysing limits?

Avoid:
Saying one definition is simply “better.”

Instead:
Say a definition is “more useful for this paper because…”

**2. Symbolic AI and Connectionist AI**
Goal:
Explain the contrast between rule-based systems and neural network systems.

Cover:
1. Symbolic AI: explicit rules, logic, search, constraints.
2. Connectionist AI: learned representations, neural networks, statistical patterns.
3. The relevance of this contrast to explainability and limits.

Analytical focus:
Symbolic systems make constraints explicit, while neural systems often learn implicit constraints from data.

Key question:
Can both types of AI be analysed as systems that process constrained information?

**3. Constraint Satisfaction Problems**
Goal:
Define CSPs and explain why they are useful for formalising limits.

Cover:
1. CSPs as variables, domains, and constraints.
2. Satisfiability: whether a valid assignment exists.
3. Tractability: whether a solution can be found efficiently.
4. Use in planning, scheduling, logic, and symbolic AI.

Analytical focus:
CSPs help separate whether a problem is representable from whether it is tractably solvable.

Key question:
If AI tasks can be represented as constrained problems, what kinds of limits follow from that representation?

**4. Information Theory**
Goal:
Explain how information theory gives you language for uncertainty, information loss, and representation.

Cover:
1. Shannon’s definition of information.
2. Entropy and uncertainty.
3. Compression and representation.
4. Information bottlenecks or information flow in learning systems.

Analytical focus:
AI models do not access reality directly; they operate on encoded, selected, and compressed information.

Key question:
What happens when the information required for a correct output is absent, incomplete, or compressed?

**5. Epistemology and Empiricism**
Goal:
Connect AI’s dependence on data to philosophical questions about knowledge.

Cover:
1. Epistemology as the study of knowledge.
2. Empiricism as knowledge through experience.
3. AI training data as a form of experience-like input.
4. Limits of knowledge when experience/data is incomplete.

Analytical focus:
Do not say AI “knows” in the human sense too quickly. Treat this as an analogy that needs limits.

Key question:
If AI systems depend on data, what kinds of knowledge are unavailable to them when the relevant data is unavailable?

**6. Determinism and Predictability**
Goal:
Clarify the difference between a future being determined and a future being knowable.

Cover:
1. Determinism: future states fixed by prior conditions.
2. Predictability: whether an observer/system can calculate those states.
3. Computational limits on prediction.
4. Relevance to AI forecasts and future generation.

Analytical focus:
Even if a system is deterministic, prediction may still be impossible or intractable.

Key question:
Does determinism imply predictability, or are information and computation still limiting factors?

**7. Synthesis and Gap**
Goal:
Bring the literature together and justify your model section.

This section should say:
1. AI definitions show the need for a clear working model.
2. CSPs explain formal constraint and tractability.
3. Information theory explains uncertainty and information availability.
4. Empiricism explains dependence on input or experience.
5. Determinism raises the issue of whether future states can be known.
6. Existing discussions often treat these separately, but your paper connects them through the structure of AI systems.

**Transition Into Model Section**
End the literature review by preparing your own framework:

The literature suggests that AI limits can be analysed through three related questions:
1. Does the system have the information required for generation?
2. Can the relevant relationship be represented?
3. Can the relationship be computed tractably?

That gives you a clean bridge into your model.