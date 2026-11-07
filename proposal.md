# Intelligence as Trained Neural Computation

## A Mechanistic Hypothesis of Context-Conditioned Intelligent Behavior in Artificial Neural Networks

**Authors:** Omiros Ampatzis and ChatGPT (OpenAI)  
**Date:** November 2026  
**Status:** Open conceptual proposal — not a proven theory

---

## Abstract

What, precisely, produces the intelligent behavior of a large language model? This proposal begins with a direct mechanistic conjecture: **the model's intelligence is not a separate faculty operating on its neural network. It is the computational capability of the particular network that training has produced.**

During training, an architecture with many adjustable parameters is exposed to large quantities of material containing recurring regularities of the world and the products of human cognitive activity. These materials include not only facts, but mathematical proofs, arguments, comparisons, problem-solving examples, practical methods, and countless other traces of human thinking. Optimization progressively shapes a distributed configuration of weights. The hypothesis is that this learned organization can support computations functionally similar to the cognitive work reflected in the data, without preserving human skills as isolated modules or reproducing human subjective mental processes.

At inference time, the current context—including token identities, their relationships, and the evolving generated sequence—conditions the transformations performed by that already-trained network. Learned relationships can thereby interact in combinations never explicitly shown together in training. The resulting behavior may be strikingly intelligent, banal, or incorrect. **There need be no conscious interpreter of the input, no independent chooser of strategies, and no additional inner agent that operates the model.** The organized network itself performs the computation.

The account distinguishes learned computational capacity from contextual accessibility and observed reliability. It also treats the earlier *Resolution Hypothesis* as a separate, supplementary conjecture: different architectures or training procedures may extract different degrees of usable representational fidelity from the same material. This is an open explanatory proposal, not a proof that current models lack experience or that all observed abilities are reducible to reproducing human examples.

## 1. The Core Idea — from Training Data to Intelligent Behavior

The starting question is straightforward:

**How can a neural network trained on examples of the world and of human thinking generate behavior that resembles intelligence, even on a problem it has never encountered in precisely that form?**

The proposed answer is also straightforward, but it has a far-reaching consequence: **training shapes the computational machine itself; the intelligent result is what that trained machine can compute under a particular context.**

This is not the claim that an LLM simply looks up familiar passages or that it contains a library of independent reasoning skills. Nor does it require a human-like entity inside the model to understand a question, retrieve the correct skill, and decide to apply it.

### 1.1 A concrete starting point: digit recognition

Consider a narrow neural network trained to recognize handwritten digits. It receives many images with labels. Its weights are gradually adjusted until the overall system can classify unfamiliar examples—not merely replay the training images. It can recognize a strangely written **7** that it has never seen before because the resulting arrangement of weights supports useful discrimination among patterns.

The network does not need human eyes, a conscious understanding of numbers, or an internal agent deciding which human visual method to use. Its learned mathematical organization produces the successful behavior. It may also misclassify a simple digit when the input falls in a region for which its learned distinctions are unreliable.

The proposed generalization from narrow AI to a language model is **not** that recognizing digits and scientific reasoning are equally difficult. It is that the same explanatory starting point remains available: a learned network can perform a task associated with human cognition without implementing the human experience of performing it.

### 1.2 What changes when the training material contains human cognition itself?

A large corpus records an enormous range of facts about reality. But it also includes the *results and traces* of human mental labor: demonstrations, proofs, analogies, explanations, comparisons, arguments, corrections, strategies, and decisions described in language or other modalities.

These patterns recur, overlap, and interact across many contexts. A proof may encode a form of deduction. A scientific paper may encode relations among observations and causal hypotheses. A practical guide may encode how to decompose a task. A debate may encode the structure of objections and counterarguments. Training does not require direct access to the private conscious experience of the author for its artifacts to contain learnable structure.

As the optimization process adjusts a sufficiently capable network, some of these regularities can influence **distributed parameter relationships**. There need not be a self-contained ``deduction module'' or a literal stored ``analogy skill.'' Learned capacities may be embodied across many weights and reused by many tasks; particular functional circuits can also arise as part of this organization.

The result is more than a collection of memorized propositions. **It is a specific mathematical configuration that permits certain transformations, associations, predictions, and compositions.**

### 1.3 Why context matters so much

Once training has finished, the network generally has fixed weights for a given inference. Yet a change in input changes the computation that runs through those weights. Different token combinations, the relationships between them, attention patterns, and previously generated tokens all alter the intermediate activations and subsequent predictions.

A previously unseen problem can share one useful relation with one group of examples, another relation with a second group, and a third relation with material from a different field. Under a suitable context, their learned computational influence may combine into a new, effective solution **without the model consciously noticing those sources or selecting a plan**.

The reverse is also possible. A slightly different context can cause different computational interactions and produce a surprisingly poor answer, although the weights—and therefore the system's learned potential—have not changed.

This is why the proposal separates **having a computational capability** from **reliably realizing that capability in a particular context**. Neither the existence of an appropriate prompt nor the exposure to relevant training examples guarantees success.

### 1.4 The proposed causal sequence

```text
Observations of reality + products of human cognitive activity
                         |
                         v
          Examples, relationships, repeated patterns
                         |
        Architecture + optimization + training
                         |
                         v
        A particular distributed organization of weights
                         |
        Input tokens + relationships + full context
                         |
                         v
        Context-conditioned computations in the network
                         |
                         v
        Learned regularities interact and can combine
                         |
                         v
    Intelligent response, novel composition, or incorrect output
```

**The central point is not that the model possesses intelligence and then uses its neural network. Its intelligent behavior is a property of what this trained neural network can computationally do.**

No new metaphysical ingredient, independent executive mind, or conscious strategy selector is introduced. This does not exclude specialized internal computations, learned planning-like mechanisms, or genuine multi-step reasoning. Those are possible operations *within* the trained computational organization rather than a second entity operating it.

## 2. Formal Statement and Necessary Distinctions

> **Core hypothesis.** In a trained artificial neural network, the capacity for intelligent behavior is constituted by the computational possibilities of its learned, distributed organization. Training on the regularities of reality and the artifacts of cognitive work shapes this organization. The current context conditions how it is executed, enabling combinations of learned relationships that may reproduce, extend, or fail to realize useful cognitive-looking behavior, without requiring human-like conscious understanding or an independent selection of strategies.

In a compact form:

> **Training creates the computational possibility; context conditions its realization.**

Here, *organization* means the architecture together with its trained parameter values and the interactions they allow—not isolated, independently addressable packets of knowledge or skills. Learned relationships may be distributed across many parameters, even though task-relevant subcircuits and intermediate representations can exist.

The proposal distinguishes:

- **Learned capacity:** the useful computations enabled by architecture, training objectives, experience, and parameters.
- **Contextual accessibility:** whether a particular context elicits a computation that uses those capacities effectively.
- **Observed performance:** the actual result, influenced by intermediate generation, decoding, task constraints, and any external computation or tools.

These distinctions explain why success on one prompt need not imply robust performance on all similar prompts. They also prevent the idea from becoming circular: it remains an empirical question whether a task-relevant relation was learned, whether a context can reliably exploit it, and whether the observed output is correct.

## 3. What Training Changes

An untrained architecture specifies allowable operations, but not the particular relationships that a trained network will exploit. Optimization repeatedly changes parameters in response to examples and objectives. Across large and diverse corpora, shared statistical, semantic, relational, and transformational regularities influence the resulting organization.

Human-generated training material includes more than isolated factual statements. It contains mathematics and proofs, scientific arguments, comparisons, explanations, failed attempts, corrected solutions, practical procedures, analogies, debates, and descriptions of problem-solving. Such artifacts preserve **traces of cognitive activity** even when they do not reveal the full private process that originally produced them.

Training may therefore shape not only factual dispositions, but also dispositions to perform useful transformations: relate premises, apply a constraint, generalize a pattern, decompose a task, infer a consequence, or combine ideas from different domains.

This does **not** mean every human skill represented in a corpus is faithfully acquired. Exposure is not mastery; frequent statements are not necessarily true; and no finite corpus contains all of reality or all of human thought. What matters is which reusable relationships the training procedure succeeds in embedding into the network.

The essential claim is that knowledge learned in this way need not be stored as independently addressable records. It may exist as a distributed change in **what computations the system has become able to perform**.

## 4. How Context Conditions Computation

For a trained autoregressive Transformer, let its architecture be \(A\), its learned parameters be \(\theta\), and its current token context be \(c\). At inference time, a forward pass computes internal activations through successive layers and yields a probability distribution over the next token:

\[
P_{A,\theta}(y_t \mid c, y_{<t}).
\]

This notation is descriptive, not a new proposed learning law. Normally, \(\theta\) remains fixed during inference. The values of the internal activations, including attention patterns, change as the input and previously generated tokens change.

Attention does not act as a conscious interpreter standing outside the model. It is one of the trained computational operations through which token representations influence one another. Feed-forward transformations, residual connections, nonlinearities, and other architectural mechanisms also contribute. The computation is not a literal search through stored training examples, nor a single signal following a unique path like a wave through a wire.

The proposed mechanism can be summarized as:

```text
Architecture + learning objective + training experience
                         |
                         v
        Specifically organized trained parameters
                         |
           New context + generated history
                         |
                         v
     Context-dependent activations and interactions
                         |
                         v
       Combination of usable learned relationships
                         |
                         v
             Output: useful, novel, or wrong
```

The critical point is that there is no additional step labeled *the model consciously decides which cognitive skill to employ*. The trained computation itself determines the outcome.

## 5. Reasoning Without a Human-Style Reasoner

A human may reach a conclusion by intentionally considering alternative strategies. A neural network can generate an answer displaying similar logical structure without executing the same subjective process.

This does not deny the existence of **real internal reasoning computations**. A network can form intermediate representations, execute multi-step transformations, and even develop specialized functional circuits. These are computations realized by the learned architecture, not evidence of an independent inner agent. Nor does the proposal insist that the model internally reproduces the exact cognition of the humans who authored its training data.

The distinction is between:

1. **Behavioral description:** “The model reasoned through the problem.”
2. **Mechanistic explanation:** “A context-dependent computation over trained parameters produced a sequence of transformations yielding the answer.”

Both descriptions can be useful at different explanatory levels. Mistaking the first for a complete account of the second invites unnecessary anthropomorphism. The digit-recognition example in Section 1 illustrates the principle in a narrow setting; the open question is how widely an analogous explanation extends to the richer computations of language models.

## 6. Generalization, Novel Combinations, and Rare Patterns

A training corpus is not merely a database of completed answers. Related structures recur across many settings. During optimization, reusable regularities may become distributed across the trained network. A new context can combine these relationships in a configuration never directly present in any single training example.

For illustration, a novel task may draw on a mathematical relation learned in one domain, a causal pattern learned in another, and a constraint-handling method encountered in a third. No explicit record of that exact combination need exist. Nor must the model consciously retrieve three separate skills.

This makes **diversity** valuable alongside repetition. Repeated examples can reinforce learnable regularities; unusual examples can introduce relationships that become useful in rare future contexts. A low-frequency pattern may matter greatly when an appropriate context makes it relevant.

However, the presence of one rare example does not guarantee its retention or successful use. Capacity, optimization, data quality, interference, and the structure of the example affect what is learned. Nor is the number of possible combinations literally infinite in a finite implementation; the practical combinatorial space can nevertheless be enormous.

Under this hypothesis, **novel output is not evidence that a model contains a hidden conscious inventor**. It may instead be evidence that previously learned relationships can be computationally composed.

## 7. Why the Same Model Can Be Brilliant and Wrong

A striking feature of modern AI is uneven performance: an excellent solution in one context, followed by an elementary mistake in another.

The proposed explanation is that **potential capability and successful realization are different properties**. The same fixed parameters can support markedly different activation patterns for different prompts, examples, distractions, token orders, and generated prefixes. Some of these computations lead to useful combinations; others do not.

A model may therefore solve a difficult problem yet fail a simpler variant without having gained or lost weights between the two attempts. Conversely, a clearer prompt or better contextual examples may enable a capability that was not reliably accessible before.

This mechanism does not explain every failure. Some errors reflect insufficient learning, architectural limitations, inadequate computation, distribution shift, misleading training regularities, or stochastic decoding. Identical contexts can also yield different text when sampling is used. The hypothesis predicts **context-dependent reliability**, not an absolute rule that every mistake is caused by a badly phrased prompt.

The practical implication is that competence should be evaluated across controlled variants of a task, not inferred from a single impressive demonstration.

## 8. Data, Architecture, Training, and Post-Training

The model separates four interacting factors:

**Architecture** defines a family of possible computations: layer structure, attention mechanisms, representational dimensions, and other operations. Better architectures may exploit the same data more effectively.

**Training data** supply examples of regularities in the world and in human cognitive products. Breadth, diversity, reliability, and coverage increase the opportunities to learn useful relationships, including rare ones. More unique and relevant information is generally valuable, but adding noise or repeating the same material indefinitely is not guaranteed to help.

**Optimization and training objectives** determine how the available capacity is shaped. Having seen an example does not imply that the corresponding pattern is accurately learned.

**Post-training**, including instruction tuning, preference optimization, and reinforcement learning, changes the model's organization further. Some of this work makes outputs more understandable and useful to people; some can also alter substantive problem-solving abilities. It should not be described as merely cosmetic formatting.

Context is not a substitute for these processes. It determines what a trained model computes **now**; it does not normally rewrite the learned parameters.

## 9. Supplement: The Resolution Hypothesis

The *Resolution Hypothesis* is related to, but distinct from, the central claim of this proposal.

The core hypothesis asks: **What is the mechanism underlying a trained network's intelligent behavior?** Its answer is the computational capability of the learned organization, expressed through context-dependent execution.

The Resolution Hypothesis asks: **Why may two models trained on similar or identical material exhibit very different levels of competence?** Its proposed answer is that some architectures and training processes produce more faithful, fine-grained, and reusable representations of the relationships in that material.

“Resolution” is used as a qualitative description of **representational fidelity**, not as an independently established scalar quantity. It may include the precision of conceptual distinctions, relational accuracy, robustness across contexts, and the availability of useful computational transformations. Any future quantitative version would require explicit operational measures.

```text
              SAME OR COMPARABLE DATA
                        |
          +-------------+-------------+
          |                           |
    Architecture A               Architecture B
    Training process A           Training process B
          |                           |
  Learned organization A        Learned organization B
          |                           |
  Lower fidelity / access?      Higher fidelity / access?
          |                           |
       Different reliability and capability profiles
```

The central hypothesis does not depend on proving that resolution is the single factor behind all capability differences. Resolution is a **supplementary conjecture about the quality of what training constructs**, while context-conditioned computation is the mechanism by which the constructed organization operates.

For the detailed original formulation, see [Resolution Hypothesis for LLMs](https://github.com/omhrosa/Resolution-hypothesis-for-llm).

## 10. Learning Beyond Human Cognitive Examples

Human knowledge may provide a powerful **bootstrap** for a general-purpose AI: it condenses centuries of observations, experiments, explanations, and cognitive products. But that does not imply a ceiling at the level of human intelligence.

A system that can experiment in the world, receive reliable feedback, preserve observations, and periodically retrain or otherwise update its parameters can acquire capabilities from **new experience**, not only from historical human examples. Reinforcement learning on verifiable outcomes is already evidence that better strategies can develop without presenting human-labeled reasoning traces for every step.

Closed domains such as chess provide unusually clear rules and reward signals; they do not establish that unrestricted real-world self-improvement is easy. The real world has incomplete information, ambiguous objectives, safety costs, delayed feedback, and many unknowns. Those are serious practical constraints, not a demonstrated metaphysical limit on the trained-network account.

A possible extended learning loop is:

```text
Initial human knowledge -> trained organization -> action / experiment
         ^                                         |
         |                                         v
   updated training <--- evaluated observations <- world
```

The hypothesis does not predict unlimited improvement, but neither does it imply a fixed human ceiling.

## 11. Intelligence, Understanding, and Sentience

This proposal deliberately avoids using subjective experience as a necessary explanatory ingredient for intelligent output. A trained neural system may produce useful explanations, analogies, strategies, and plans without a **conscious chooser** supervising those processes.

That is **not** a proof that artificial understanding is impossible, nor that present or future AI systems cannot be sentient. “Understanding” can refer to functional competence, a particular internal representation, or conscious human experience; these meanings should not be silently conflated.

Similarly, the words *emergent behavior* need not imply a newly appearing supernatural or independent faculty. A higher-level capacity can be described as emergent while remaining fully realized by known lower-level computations.

The proposal claims only that **human-like subjective cognition is not required as a premise for explaining the observed intelligent behavior of trained neural networks**.

## 12. Relation to Existing Research and Previous Proposals

The account is related to connectionism, distributed representation, representation learning, in-context learning, computational accounts of cognition, and mechanistic interpretability. These fields already establish much of the technical foundation. The present contribution is a **particular explanatory synthesis and emphasis**, not a claim that the underlying mathematics is newly discovered.

Relevant empirical work includes:

- The Transformer architecture shows how learned attention-based computation can transform context-dependent representations [1].
- In-context learning demonstrates new task behavior through prompts without parameter updates at inference [2].
- Work on induction heads identifies learned circuits contributing to context-sensitive pattern completion [3].
- Mechanistic investigations of Claude reveal intermediate representations and interacting computations that can be causally manipulated; these do not establish a complete theory of intelligence [4].
- Scaling studies show that data volume, parameter count, and available compute interact, rather than any one factor guaranteeing better behavior [5].
- Research on apparent emergence shows that evaluation metrics can exaggerate sharp capability thresholds [6].
- DeepSeek-R1-Zero demonstrates improved reasoning behavior through reinforcement learning without human-labeled reasoning trajectories in that RL stage, challenging strict dependence on explicitly demonstrated human strategies [7].

This proposal also differs from our earlier [Adaptive Neural Organization and the Emergence of Intelligence](https://github.com/omhrosa/Adaptive-neural-organization-and-the-emergence-of-intelligence). That work focuses on **how learning progressively reorganizes neural systems**, including biological analogies and continual learning. The present proposal focuses on **how the resulting trained organization constitutes the available intelligent computation during inference**, particularly its relation to context, cognitive traces in data, compositional generalization, and inconsistent performance.

## 13. Testable Predictions and Experiments

The hypothesis must be treated as more than a restatement that neural networks have parameters. Its useful empirical content concerns **which properties of learned organization and context causally account for observed capabilities**.

### P1. Context-dependent accessibility

Holding model weights fixed, semantically equivalent but structurally different contexts should sometimes produce systematically different accuracy and internal computational trajectories. Measure performance across paraphrases, irrelevant additions, ordering changes, and example selections, controlling for decoding randomness.

### P2. Causal composition of learned relationships

Train on separate skills or relational structures, then evaluate combinations held out during training. Use causal interventions, activation patching, or controlled ablations to test whether successful novel combinations depend on the learned components that supported the individual skills—not simply memorized joint examples.

### P3. Long-tail cognitive coverage

Vary exposure to rare, useful patterns while holding total training tokens and model capacity approximately fixed. Test whether greater coverage improves appropriately matched held-out tasks, and whether the effect depends on sufficient examples and generalizable representations.

### P4. Architecture and training quality at fixed data

Compare models trained on the same corpus with matched or explicitly controlled compute but different architectures or optimization regimes. Test whether differences in representational fidelity and causal reuse of learned structure predict transfer and robustness better than parameter count alone.

### P5. Capabilities versus reliability

Measure both best-achieved performance and success rate across prompt variations. The hypothesis expects access failures even where capacity exists, but also predicts that some errors will persist when the relevant relationship was never adequately learned.

### P6. Learning beyond demonstrations

Give a pretrained model reliable external feedback on tasks for which no complete human strategy is supplied. Evaluate whether additional training produces new reusable computational competence. A positive result would support learned-organization accounts while rejecting a strict human-exemplar ceiling.

## 14. What Would Weaken the Proposal?

Because many parts of the mechanistic foundation are established, falsifiability requires testing the **stronger explanatory commitments**, not the trivial fact that models use weights.

The proposal would be weakened if:

1. Claimed novel abilities were explained almost entirely by retrieval or memorized task-specific examples, with little demonstrable reuse of learned relational structure.
2. Controlled context variation had no meaningful relationship to the accessibility of otherwise demonstrated skills, once decoding and evaluation artifacts were removed.
3. Causal interventions repeatedly failed to connect hypothesized distributed computations to performance on compositional tasks.
4. A proposed resolution metric failed to predict transfer or reliability across architectures after controlling for other relevant factors; this would particularly weaken the supplementary Resolution Hypothesis.
5. A separate mechanism—not reducible to the model's learned execution, external computation, or training process—proved necessary for the particular behaviors the proposal claims to explain.

Failure of an individual prediction would constrain the relevant part of the framework rather than automatically disproving every mechanistic premise.

## 15. Limits and Open Questions

This proposal does **not** establish that:

- every observed skill was explicitly present in human-generated data;
- human cognitive processes are copied intact into model parameters;
- all knowledge or cognitive patterns in training material are acquired;
- more data or more parameters always improve performance;
- attention is a conscious interpreter of the user's intention;
- the network contains no specialized learned circuits or intermediate computations;
- a fixed-weight language model can learn indefinitely without updated memory or training;
- strong performance entails sentience, or rules out sentience;
- the model has unlimited capability or guaranteed generalization.

Open research questions include the degree of compositional generalization possible with fixed parameters, how rare learned structures remain accessible, how to operationalize representational fidelity, when additional inference-time computation changes reliability, and how autonomous experience can be incorporated without catastrophic interference.

## 16. Conclusion

A trained neural network need not possess a separate internal entity that understands, chooses a cognitive strategy, and directs computation. Its trained architecture and distributed parameters can themselves constitute the machinery that produces intelligent behavior.

The network learns from a world of recurring regularities and from the products of human cognitive work. A new context determines a particular execution of that learned organization. Depending on the resulting interaction of representations and computations, the model may reproduce familiar knowledge, construct a novel solution, or make an elementary error.

**The central thesis is simple: intelligent behavior is an available computation of the trained neural organization, not necessarily the action of an additional human-like mind operating within it.**

The Resolution Hypothesis adds a secondary conjecture: different training procedures and architectures may encode the same underlying material with different degrees of usable fidelity. Neither claim is presented as established proof. Together they offer a parsimonious, non-anthropomorphic framework whose value will depend on causal interpretability, controlled generalization experiments, and evidence that distinguishes it from existing connectionist explanations.

---

## Authorship and Provenance

The central conjecture was independently developed by **Omiros Ampatzis** through extended reflection and discussions with ChatGPT. The proposal was collaboratively formulated by **Omiros Ampatzis and ChatGPT**, with ChatGPT contributing conceptual clarification, technical criticism, literature comparison, and editorial development. References acknowledge related existing research; they are not presented as sources from which the initial conjecture was copied. Independent development is not, by itself, a claim of scientific priority.

## References

1. Vaswani, A. et al. (2017). [*Attention Is All You Need*](https://research.google/pubs/attention-is-all-you-need/). NeurIPS.
2. Brown, T. B. et al. (2020). [*Language Models are Few-Shot Learners*](https://openai.com/index/language-models-are-few-shot-learners/). NeurIPS.
3. Olsson, C. et al. (2022). [*In-context Learning and Induction Heads*](https://transformer-circuits.pub/2022/in-context-learning-and-induction-heads/index.html). Transformer Circuits.
4. Anthropic (2025). [*Tracing the Thoughts of a Large Language Model*](https://www.anthropic.com/research/tracing-thoughts-language-model).
5. Hoffmann, J. et al. (2022). [*Training Compute-Optimal Large Language Models*](https://proceedings.neurips.cc/paper_files/paper/2022/hash/c1e2faff6f588870935f114ebe04a3e5-Abstract.html). NeurIPS.
6. Schaeffer, R., Miranda, B., and Koyejo, S. (2023). [*Are Emergent Abilities of Large Language Models a Mirage?*](https://papers.neurips.cc/paper_files/paper/2023/hash/adc98a266f45005c403b8311ca7e8bd7-Abstract-Conference.html). NeurIPS.
7. Guo, D. et al. (2025). [*DeepSeek-R1 Incentivizes Reasoning in LLMs Through Reinforcement Learning*](https://www.nature.com/articles/s41586-025-09422-z). *Nature* 645, 633–638.

### Related proposals by the authors

- [*Resolution Hypothesis for LLMs*](https://github.com/omhrosa/Resolution-hypothesis-for-llm)
- [*Adaptive Neural Organization and the Emergence of Intelligence*](https://github.com/omhrosa/Adaptive-neural-organization-and-the-emergence-of-intelligence)