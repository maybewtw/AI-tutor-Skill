# Source Policy

## Source hierarchy

1. **Primary**: research papers, standards, university course material, and
   official model/framework documentation. Use these for definitions, claims,
   limits, and version-specific behavior.
2. **Curated secondary**: textbooks, reputable courses, and technical tutorials
   with named authors, references, and reproducible examples. Use these for
   intuition and sequencing.
3. **Practitioner**: engineering blogs, case studies, talks, and postmortems.
   Use these for trade-offs and real-world patterns, not universal definitions.
4. **Discovery only**: social posts, unsourced summaries, and AI-generated
   explanations. These may suggest a lead but should not be canonical evidence.

## Selection checklist

For each candidate source record:

- author or organization;
- source type and intended audience;
- publication or last-updated date;
- exact topics or claims covered;
- prerequisites;
- whether examples are reproducible;
- known version or vendor scope;
- URL or local path;
- date last checked.

Prefer a small set of complementary sources over a large link dump. A good
starter set usually has one rigorous foundation, one accessible explanation,
one practical implementation reference, and one product/case source.

## Verification workflow

1. Define the claim or learning objective before collecting material.
2. Find a primary source for the claim where possible.
3. Cross-check important or surprising claims with another independent source.
4. Run the example, inspect the stated assumptions, or test a counterexample.
5. Record conflicts instead of silently choosing one; explain whether they arise
   from terminology, scope, or version differences.
6. Separate stable concepts from fast-changing implementation details.
7. Add a `verified_at` date and review volatile entries regularly.

## Recommended starter sources

- [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course/): practical foundations and exercises.
- [Stanford CS229 materials](https://cs229.stanford.edu/materials/handout.pdf): rigorous classical machine learning foundations.
- [Hugging Face LLM Course](https://huggingface.co/learn/llm-course/en/chapter0/1): transformers, datasets, fine-tuning, and the open source LLM ecosystem.
- [OpenAI Evals documentation](https://platform.openai.com/docs/api-reference/evals/deleteRun): an example of official guidance for evaluating model and system behavior.
- Official vendor documentation: current API behavior, limits, and examples.
- Official evaluation documentation or standards: how to measure system quality.

The tutor should link to the actual source used, never fabricate a citation, and
state when a recommendation is an inference rather than a source-backed fact.
