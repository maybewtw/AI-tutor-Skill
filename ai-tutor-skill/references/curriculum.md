# AI Curriculum Map

Use this map as a dependency guide, not a rigid checklist. Skip or compress a
topic only after checking whether it is a prerequisite for the learner's goal.

## 0. Mental models and prerequisites

- AI vs. machine learning vs. deep learning vs. generative AI
- Data, representation, model, training, inference, and feedback
- Basic probability, statistics, vectors, functions, and experimentation
- Optional implementation basics: Python, NumPy, and data handling

## 1. Machine learning foundations

- supervised, unsupervised, and reinforcement learning
- features, labels, parameters, loss, and optimization
- train/validation/test splits and data leakage
- overfitting, regularization, generalization, and bias/variance
- classification, regression, ranking, and core metrics
- baselines, experiments, error analysis, and monitoring

## 2. Deep learning

- neural networks and representations
- activations, gradients, backpropagation, and optimizers
- embeddings and similarity
- sequence modeling and attention
- training dynamics, compute, and inference constraints

## 3. Transformers and LLMs

- tokenization, embeddings, positional information, and attention
- pretraining, supervised fine-tuning, preference/post-training concepts
- context windows, decoding, hallucination, and tool use
- prompting, structured output, and context engineering
- fine-tuning, retrieval augmentation, and when not to use them

## 4. AI application frameworks

- RAG: ingestion, chunking, embedding, retrieval, reranking, generation
- agents: model, instructions, tools, state, planning, and guardrails
- workflows vs. agents and deterministic orchestration
- evaluation datasets, graders, human review, and regression tests
- latency, cost, reliability, observability, privacy, and safety

## 5. AI product and platform practice

- problem selection and workflow redesign
- human-in-the-loop and trust calibration
- UX for uncertainty, citations, correction, and recovery
- quality, business, adoption, and operational metrics
- data and feedback loops
- feature vs. workflow vs. platform capability
- rollout, experimentation, governance, and lifecycle management

## Suggested sequence

For a learner who is new to AI but works in platform products:

```text
mental models -> ML foundations -> embeddings/attention -> transformers/LLMs
-> RAG and agents -> evaluation/reliability -> AI product/platform practice
```

Use a top-down preview of the whole map at the beginning of a learning cycle.
Use bottom-up depth only for concepts needed by the current milestone.
