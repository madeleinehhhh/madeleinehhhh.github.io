# AI & Machine Learning: A Self-Directed Syllabus for the Analytically Minded Developer

*Tailored for backgrounds in analytic philosophy and web development*

This syllabus is organized into five modules that build on each other, moving from intellectual history and conceptual foundations through to hands-on development and frontier research questions. Each module can take 2–6 weeks depending on depth of engagement. Resources are curated for someone who thinks carefully about concepts and can read technical material, but who is approaching ML from the outside.

---

## Module 1: Intellectual History & Conceptual Foundations

Before touching any code, it pays to understand the long arc of AI research — the debates, the dead ends, and why the current moment looks the way it does. Your philosophy background gives you a real advantage here.

### Core Reading

| Type | Resource | Why It Matters |
|------|----------|----------------|
| Book | [Machines Who Think — Pamela McCorduck](https://web.archive.org/web/20200301043518/http://www.pamelamc.com/html/machines_who_think.html) ⭐ *Essential* | Definitive intellectual history of AI from antiquity to the 1980s. Readable narrative history. |
| Essay | [Alchemy and AI — Hubert Dreyfus (1965)](https://www.rand.org/pubs/papers/P3244.html) 🔹 *Philosophy* | The foundational philosophical critique of early symbolic AI. Deeply relevant to philosophy of mind debates. |
| Book | [What Computers Can't Do — Hubert Dreyfus](https://archive.org/details/whatcomputerscan00drey) 🔹 *Philosophy* | Dreyfus's full case against symbolic AI and the rationalist tradition. Read alongside the rebuttal literature. |
| Article | [A Proposal for the Dartmouth Summer Research Project on AI (1955)](http://jmc.stanford.edu/articles/dartmouth/dartmouth.pdf) | The founding document of AI as a field. Short, historically revealing. |
| Essay | [Computing Machinery and Intelligence — Alan Turing (1950)](https://www.csee.umbc.edu/courses/471/papers/turing.pdf) ⭐ *Essential* | The original Turing Test paper. Still philosophically rich and surprisingly readable. |
| Article | [Minds, Brains, and Programs — John Searle (1980)](https://www.cambridge.org/core/journals/behavioral-and-brain-sciences/article/abs/minds-brains-and-programs/DC644B47A4299C637C89772FACC2706A) 🔹 *Philosophy* | The Chinese Room argument. Essential reading given current debates about LLM understanding. |

### Supplemental

| Type | Resource | Why It Matters |
|------|----------|----------------|
| Podcast | [Lex Fridman #302 — Yann LeCun](https://lexfridman.com/yann-lecun-3/) | LeCun's skepticism about current architectures. Good intro to live debates about what's missing. |
| Essay | [The Bitter Lesson — Rich Sutton (2019)](http://www.incompleteideas.net/IncIdeas/BitterLesson.html) ⭐ *Essential* | Influential short essay arguing that general methods beat human-engineered solutions. Sparks real debate. |

---

## Module 2: How Neural Networks Actually Work

Build genuine intuition for what is happening inside these models before diving into theory. The goal is geometric and mechanical understanding, not just metaphor.

### Video Series (Watch First)

| Type | Resource | Why It Matters |
|------|----------|----------------|
| Video | [But what is a neural network? — 3Blue1Brown](https://www.youtube.com/watch?v=aircAruvnKk) ⭐ *Essential* | The best visual introduction to neural nets. Watch all 4 episodes in the series. |
| Video | [Neural Networks: Zero to Hero — Andrej Karpathy](https://karpathy.ai/zero-to-hero.html) ⭐ *Essential* | Builds a GPT from scratch in Python. Exceptional explanations. Do the coding exercises. |
| Video | [Transformers from Scratch — Andrej Karpathy (makemore series)](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) 🔧 *Technical* | Continuation of Zero to Hero, focuses on attention mechanisms. |

### Articles & Blog Posts

| Type | Resource | Why It Matters |
|------|----------|----------------|
| Blog | [The Illustrated Transformer — Jay Alammar](https://jalammar.github.io/illustrated-transformer/) ⭐ *Essential* | The clearest visual walkthrough of the transformer architecture. Essential companion to the original paper. |
| Blog | [The Illustrated GPT-2 — Jay Alammar](http://jalammar.github.io/illustrated-gpt2/) | Extends the transformer post to autoregressive language models. Concrete and well-illustrated. |
| Blog | [Lilian Weng's Blog](https://lilianweng.github.io/) 🔧 *Technical* | Research scientist at OpenAI; deep technical posts on attention, RL, diffusion. High-quality reference. |
| Paper | [Attention Is All You Need (2017)](https://arxiv.org/abs/1706.03762) | The transformer paper. Dense, but worth reading once you have the illustrated versions as scaffolding. |

### Books

| Type | Resource | Why It Matters |
|------|----------|----------------|
| Book | [Deep Learning — Goodfellow, Bengio, Courville (free online)](https://www.deeplearningbook.org/) 🆓 *Free* | The standard graduate textbook. Use as reference rather than reading cover to cover. |
| Book | [Hands-On Machine Learning — Aurélien Géron](https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1098125975) | Practical, code-first introduction. Great bridge between intuition and implementation. |

---

## Module 3: The LLM Revolution — From GPT to Now

Understand the specific developments that led to the current generation of large language models — scaling laws, RLHF, and the emergence of surprising capabilities.

### Key Papers (Read in Order)

| Type | Resource | Why It Matters |
|------|----------|----------------|
| Paper | [Scaling Laws for Neural Language Models (2020)](https://arxiv.org/abs/2001.08361) ⭐ *Essential* | The paper that made scaling compute and data the dominant research strategy. Philosophically interesting on emergence. |
| Paper | [Language Models are Few-Shot Learners / GPT-3 (2020)](https://arxiv.org/abs/2005.14165) | The GPT-3 paper. Introduced in-context learning. Read the introduction and results sections at minimum. |
| Paper | [Training language models to follow instructions with human feedback (InstructGPT)](https://arxiv.org/abs/2203.02155) ⭐ *Essential* | How RLHF works. The technique behind ChatGPT. Readable and important. |
| Paper | [Sparks of AGI — Microsoft Research (2023)](https://arxiv.org/abs/2303.12528) | Controversial but worth reading as a document of the current moment. Raises real philosophical questions. |

### Articles & Explainers

| Type | Resource | Why It Matters |
|------|----------|----------------|
| Blog | [What Is ChatGPT Doing and Why Does It Work? — Stephen Wolfram](https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/) ⭐ *Essential* | Long but accessible. Good for conceptual understanding without heavy math. |
| Article | [Stochastic Parrots — Bender et al. (2021)](https://dl.acm.org/doi/10.1145/3442188.3445922) 🔹 *Philosophy* | Influential critical perspective on LLMs. Raises questions about meaning and statistical correlation. |
| Blog | [The AI Hype Cycle Is Distracting Us — Gary Marcus](https://garymarcus.substack.com/) | Marcus's ongoing skeptical commentary. Good counterweight to enthusiasm. Follow his Substack. |
| Newsletter | [Import AI — Jack Clark](https://importai.substack.com/) | Weekly newsletter by co-founder of Anthropic. Tracks research developments with good editorial judgment. |

### Podcasts for Context

| Type | Resource | Why It Matters |
|------|----------|----------------|
| Podcast | [80,000 Hours — Interview with Paul Christiano](https://80000hours.org/podcast/episodes/paul-christiano-ai-alignment-solutions/) | Alignment researcher on what the hard problems actually are. Rigorous and honest. |
| Podcast | [MLST — Various Episodes](https://www.youtube.com/@MachineLearningStreetTalk) 🔧 *Technical* | Technical podcast with researchers. Higher level than Lex Fridman, good once you have foundations. |

---

## Module 4: Hands-On Development

This is where your web development background becomes directly useful. The goal is to build things — starting with API calls and moving toward understanding embeddings, retrieval, and agents.

### Learn Python Basics (if needed)

| Type | Resource | Why It Matters |
|------|----------|----------------|
| Course | [Python for Everybody — Dr. Chuck (Coursera/free)](https://www.py4e.com/) 🆓 *Free* | Best beginner Python course for people coming from other languages. Free materials available. |
| Book | [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/) 🆓 *Free* | Practical Python. Free online. Good for someone who learns by doing. |

### API & Prompt Engineering

| Type | Resource | Why It Matters |
|------|----------|----------------|
| Docs | [Anthropic API Documentation](https://docs.anthropic.com/) ⭐ *Essential* | Start here for building with Claude. Well-written docs with good examples. |
| Docs | [OpenAI Cookbook](https://cookbook.openai.com/) | Practical examples of common LLM tasks. Most patterns translate to any provider. |
| Article | [Prompt Engineering Guide](https://www.promptingguide.ai/) | Comprehensive guide to prompting techniques. Good reference for chain-of-thought, few-shot, etc. |

### Embeddings & RAG (Closest to Your Drupal Work)

| Type | Resource | Why It Matters |
|------|----------|----------------|
| Blog | [What are embeddings? — Simon Willison](https://simonwillison.net/2023/Oct/23/embeddings/) ⭐ *Essential* | Clear explanation of vector embeddings for a developer audience. Simon's blog is excellent generally. |
| Tutorial | [Building RAG Applications — LangChain Docs](https://python.langchain.com/docs/use_cases/question_answering/) | Step-by-step guide to retrieval-augmented generation. Connects your content modeling intuitions to AI. |
| Blog | [Vector databases explained — Pinecone](https://www.pinecone.io/learn/vector-database/) | Practical intro to the database layer that makes semantic search possible. |

### Courses

| Type | Resource | Why It Matters |
|------|----------|----------------|
| Course | [fast.ai — Practical Deep Learning for Coders](https://course.fast.ai/) ⭐ *Essential* | Top-down, code-first approach. Best for developers who want to build before fully understanding theory. |
| Course | [DeepLearning.AI Short Courses](https://www.deeplearning.ai/short-courses/) | 2–4 hour focused courses on specific topics (RAG, agents, fine-tuning). Very practical. |
| Course | [Full Stack Deep Learning](https://fullstackdeeplearning.com/) 🔧 *Technical* | Covers the engineering side: deployment, monitoring, data pipelines. Excellent for web devs. |

---

## Module 5: Frontier Questions & Philosophy of AI

This is where your analytic philosophy background is most valuable. The open questions in alignment, interpretability, and AI ethics are genuinely hard philosophical problems — not merely engineering challenges.

### Alignment & Safety

| Type | Resource | Why It Matters |
|------|----------|----------------|
| Essay | [AGI Safety from First Principles — Richard Ngo](https://drive.google.com/file/d/1uK7NhdSKprQKZnRjU58X7NLA1auXlWHt/view) ⭐ *Essential* | The clearest conceptual overview of why alignment is hard. Philosophically rigorous. |
| Blog | [AI Safety — Paul Christiano](https://ai-alignment.com/) | Blog by one of the leading alignment researchers. Dense but worth it. |
| Paper | [Concrete Problems in AI Safety — Amodei et al. (2016)](https://arxiv.org/abs/1606.06565) | Lays out specific technical problems in making AI systems behave as intended. |
| Book | [Human Compatible — Stuart Russell](https://www.amazon.com/Human-Compatible-Artificial-Intelligence-Problem/dp/0525558616) ⭐ *Essential* | Best book-length treatment of the alignment problem. Clear philosophical argument. |

### Interpretability — What's Actually Happening Inside?

| Type | Resource | Why It Matters |
|------|----------|----------------|
| Blog | [Transformer Circuits Thread — Anthropic](https://transformer-circuits.pub/) 🔧 *Technical* | Anthropic's ongoing research into mechanistic interpretability. Technically demanding but fascinating. |
| Article | [Zoom In: An Introduction to Circuits — Distill.pub](https://distill.pub/2020/circuits/zoom-in/) ⭐ *Essential* | Distill.pub has the best visual explanations of neural network internals. The whole site is worth exploring. |
| Blog | [Chris Olah's Blog](https://colah.github.io/) | Olah pioneered interpretability research. His older posts on neural net visualization are foundational. |

### Philosophy of Mind Connections

| Type | Resource | Why It Matters |
|------|----------|----------------|
| Paper | [Language Models and Linguistic Knowledge — Linzen (2019)](https://arxiv.org/abs/1906.07510) 🔹 *Philosophy* | Asks whether LLMs know grammar or merely predict it. Connects to debates about competence vs. performance. |
| Book | [The Language Instinct — Steven Pinker](https://www.amazon.com/Language-Instinct-How-Mind-Creates/dp/0060976519) | Background on linguistics and cognitive science. Useful context for evaluating LLM language claims. |
| Essay | [On the Measure of Intelligence — François Chollet (2019)](https://arxiv.org/abs/1911.01547) 🔹 *Philosophy* | Proposes a rigorous definition of intelligence and critiques benchmark-based evaluation. Philosophically sharp. |
| Newsletter | [The Alignment Forum](https://www.alignmentforum.org/) | Community of alignment researchers. High signal-to-noise ratio. Read the featured posts first. |

### Ongoing Sources to Follow

| Type | Resource | Why It Matters |
|------|----------|----------------|
| Blog | [Simon Willison's Blog (simonwillison.net)](https://simonwillison.net/) ⭐ *Essential* | Developer perspective on AI tools. Practical, honest, well-curated. Excellent for staying current. |
| Newsletter | [The Batch — Andrew Ng](https://www.deeplearning.ai/the-batch/) | Weekly AI newsletter with good editorial perspective. Good balance of technical and strategic. |
| Blog | [Anthropic Research Blog](https://www.anthropic.com/research) | Primary source on interpretability, alignment, and model evaluations from Anthropic. |
| Paper | [arXiv cs.AI and cs.LG sections](https://arxiv.org/list/cs.AI/recent) | Preprint server where all major ML research appears first. Follow to track the frontier. |

---

## A Note on Sequencing

You don't need to finish Module 1 before starting Module 4. A good approach is to run conceptual reading (Modules 1–2) alongside practical building (Module 4) — each will make the other more meaningful. Module 3 fills in the historical arc of recent developments and is best read once you have enough technical vocabulary from Module 2 to evaluate the claims being made.

Module 5 can begin anytime, but will hit differently once you've built something and confronted firsthand how these systems behave in ways that are hard to predict or explain.

---

*This syllabus was compiled February 2026. The field moves fast — check publication dates and supplement with recent work from arXiv and the blogs listed in Module 5.*
