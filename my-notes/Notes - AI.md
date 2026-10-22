Notes - AI



- **Feeding it the right information:** prompts, context, and retrieval from company data (RAG).
- **Letting it act:** tools, function calling, MCP servers, agents.
- **Knowing whether it works:** evaluation, test sets, LLM-as-judge.
- **Running it safely and cheaply:** guardrails, gateways, caching, routing, monitoring, cost control.





 **Book:** Preface (pp. xi–xx) and all of Chapter 1 (pp. 1–47). Read "The AI Engineering Stack" (pp. 35–47) twice; it is the map of everything that follows.


questins the book answers ? 


 Should I build this AI application?
• How do I evaluate my application? Can I use AI to evaluate AI outputs?
• What causes hallucinations? How do I detect and mitigate hallucinations?
• What are the best practices for prompt engineering?
• Why does RAG work? What are the strategies for doing RAG?
3 Teaching a course on how to use TensorFlow in 2017 taught me a painful lesson about how quickly tools and
tutorials become outdated.
• What’s an agent? How do I build and evaluate an agent?
• When to finetune a model? When not to finetune a model?
• How much data do I need? How do I validate the quality of my data?
• How do I make my model faster, cheaper, and secure?
• How do I create a feedback loop to improve my application continually?


ML concepts better to know::

Probabilistic concepts such as sampling, determinism, and distribution.
• ML concepts such as supervision, self-supervision, log-likelihood, gradient
descent, backpropagation, loss function, and hyperparameter tuning.
• Various neural network architectures, including feedforward, recurrent, and
transformer.
• Metrics such as accuracy, F1, precision, recall, cosine similarity, and cross
entropy.



why reading this ::

• You’re building or optimizing an AI application, whether you’re starting from
scratch or looking to move beyond the demo phase into a production-ready
stage. You may also be facing issues like hallucinations, security, latency, or costs,
and need targeted solutions.
• You want to streamline your team’s AI development process, making it more
systematic, faster, and reliable.
• You want to understand how your organization can leverage foundation models
to improve the business’s bottom line and how to build a team to do so.



Ai Applications on github
Education Tutoring
Essay grading
Employee onboarding
Employee upskill training
Conversational bots General chatbot
AI companion
Customer support
Product copilots
Information aggregation Summarization
Talk-to-your-docs
Summarization
Market research
Data organization Image search

Knowledge management
Document processing
Workflow automation Travel planning
Event planning
Data extraction, entry, and annotation
Lead generation



AI Projects on Github (Opensource)
https://goodailist.com/repos


https://theresanaiforthat.com/task/sops/


35–47 twice 



Students are using AI to write essays. Writers are using AI to write books.13 Many
startups already use AI to generate children’s, fan fiction, romance, and fantasy
books. Unlike traditional books, AI-generated books can be interactive, as a book’s
plot can change depending on a reader’s preference. This means that readers can
actively participate in creating the story they are reading. A children’s reading app
identifies the words that a child has trouble with and generates stories centered
around these words



For enterprises, AI can automate repetitive tasks such as lead management, invoicing,
reimbursements, managing customer requests, data entry, and so on. One especially
exciting use case is using AI models to synthesize data, which can then be used to
improve the models themselves. You can use AI to create labels for your data, looping
in humans to improve the labels. We discuss data synthesis in Chapter 8.

AI can also help with sales lead generation,


Involving humans in AI’s decision-making processes is called human-in-the-loop.



If something is
easy for you to build, it’s also easy for your competitors. What moats do you have to
defend your product?

In AI, there are generally three types of competitive advantages: technology, data, and
distribution

There are three layers to any AI application stack: application development, model
development, and infrastructure.

Application development
        With models readily available, anyone can use them to develop applications. This
        is the layer that has seen the most action in the last two years, and it is still rapidly
        evolving. Application development involves providing a model with good
        prompts and necessary context. This layer requires rigorous evaluation. Good
        applications also demand good interfaces.
Model development
        This layer provides tooling for developing models, including frameworks for
        modeling, training, finetuning, and inference optimization. Because data is central
        to model development, this layer also contains dataset engineering. Model
        development also requires rigorous evaluation.
Infrastructure
        At the bottom is the stack is infrastructure, which includes tooling for model
        serving, managing data and compute, and monitoring.




 stable diffusion ??

For enterprise use cases, AI applications still need to solve business
problems,


In general, model
adaptation techniques can be divided into two categories, depending on whether they
require updating model weights.

1. Prompt-based techniques, which include prompt engineering, adapt a model without
updating the model weights.

2. Finetuning, on the other hand, requires updating model weights.

Modeling and training refers to the process of coming up with
a model architecture, training it, and finetuning it. Examples of tools in this category
are Google’s TensorFlow, Hugging Face’s Transformers, and Meta’s PyTorch.

quantization, the process of reducing the
precision of model weights

training(pre training from random weights) / finetuneing // post training/ 



Dataset engineering. Dataset engineering refers to curating, generating, and annotating
the data needed for training and adapting AI models.

Inference optimization means making models faster and
cheaper

Inference optimization techniques, including quantization, distillation, and parallelism,

today till 105
+1 till 152
+2 till 199
