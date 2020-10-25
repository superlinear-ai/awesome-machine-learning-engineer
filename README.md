# Awesome Machine Learning Engineer

<div align="center">

<img height="280" src="https://github.com/sindresorhus/awesome/raw/main/media/logo.svg?sanitize=true" alt="Awesome">

For more awesomeness, check out [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome).

</div>

## What is this and how do I use it?

- This is a curated list of delightful resources for everything you need to develop Machine Learning solutions.
- All resources are structured as follows: *[Content level]* *[Page title]* - *[Description]* (*[Reading time]*).
  - There are three content levels:
    1. :hatched_chick: Essential reading for all ML engineers
    2. :snake: Advanced reading for professional ML engineers
    3. :unicorn: Expert material for expert ML engineers
  - Descriptions are written so that they complete the sentence *"After reading this article you will have learned to ..."*.

## Contents

- [Communication](#communication)
- [Software Engineering](#software-engineering)
- [Machine Learning](#machine-learning)
- [DevOps](#devops)

## Communication

- :hatched_chick: [BLUF: The Military Standard That Can Make Your Writing More Powerful](https://www.animalz.co/blog/bottom-line-up-front/) - Make your communication more powerful. (5 min)
- :hatched_chick: [The XY Problem](http://xyproblem.info/) - Focus on explaining your end goal when asking for help. (5 min)
- :snake: [Understanding MECE](https://strategyu.co/wtf-is-mece-mutually-exclusive-collectively-exhaustive/) - Write structured lists in your documents and communication. (10 min)
- :unicorn: [Nonviolent communication](https://medium.com/s/please-advise/the-essential-guide-to-difficult-conversations-41f736e63ccf) - Deliver constructive feedback in difficult situations. (10 min)
- :snake: [SMART criteria](https://en.wikipedia.org/wiki/SMART_criteria) - Define goals in a structured way. (5 min)
- :hatched_chick: [Sombody else's problem](https://en.wikipedia.org/wiki/Somebody_else%27s_problem) - Don't make it SEP. (1 min)
- :unicorn: [The Halo effect](https://effectiviology.com/halo-effect/) - Account for the cognitive bias that might influence the way you view others. (10 min)
- :snake: [SCQA: What is it, how does it work, and how can it help me?](https://analytic-storytelling.com/scqa-what-is-it-how-does-it-work-and-how-can-it-help-me/) - Structure your presentation, proposals, and sales outlines. (5 min)
- :hatched_chick: [E-mail like a boss](https://pbs.twimg.com/media/D7LgaoMW4Acy6hL?format=jpg&name=large) - Write better e-mails. (1 min)
- :unicorn: [Mythical Man Month - The Cliff Notes](https://8thlight.com/blog/sue-kim/2013/01/31/mythical-man-month-cliff-notes.html) - Understand the relationship between person-days and throughput time in a project (5 min)
- :hatched_chick: [Bike-shedding: how mature are you as an engineer?](https://no-kill-switch.ghost.io/bike-shedding-how-mature-are-you-as-an-engineer/) - Call out and avoid bike-shedding. (5 min)
- :hatched_chick: [Presentation Rules](http://www.jilles.net/perma/2020/06/05/presentation-rules.html) - Make your slides satisfy essential best practices. (5 min)
- :unicorn: [Four-sides model](https://en.wikipedia.org/wiki/Four-sides_model) - Carefully consider what you communicate to optimize its result. (15 min)
- :hatched_chick: [How to write in plain English](http://www.plainenglish.co.uk/how-to-write-in-plain-english.html) - Write in plain English. (15 min)
- :snake: [No More Misunderstandings](https://smallbigideas.substack.com/p/no-more-misunderstandings) - Avoid misunderstandings by paraphrasing. (15 min)


## Software Engineering

### API design

- :snake: [FastAPI docs](https://fastapi.tiangolo.com/tutorial/first-steps/) - Build RESTful APIs that correspond one-to-one with the OpenAPI spec. (1-X hours)
- :unicorn: [Zalando's RESTful API guidelines](https://opensource.zalando.com/restful-api-guidelines/) - Design sustainable REST APIs. (X hours)
- :unicorn: [Microsoft's REST API guidelines](https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md) - Design sustainable REST APIs. (X hours)
- :unicorn: [gRPC compared to REST](https://eng.fromatob.com/post/2019/05/why-were-switching-to-grpc/) - Compare the two leading solutions for communication between services. (5 min)
- :unicorn: [HTTP response headers for the responsible developer](https://www.twilio.com/blog/a-http-headers-for-the-responsible-developer) - Optimize your APIs with HTTP headers. (2 min)
- :snake: [Falsehoods programmers believe about time](http://infiniteundo.com/post/25326999628/falsehoods-programmers-believe-about-time) - Avoid most of the assumptions made about time. (2 min)
- :snake: [Falsehoods programmers believe about names](https://www.kalzumeus.com/2010/06/17/falsehoods-programmers-believe-about-names/) - Avoid most of the assumptions made about personal names. (5 min)
- :hatched_chick: [Semantic versioning](https://semver.org/) - Assign and increment version numbers of your software. (10 min)
- :unicorn: [Keep a changelog](https://keepachangelog.com/) - Keep a well-maintained changelog in your software. (10 min)

### Version control

- :snake: [Learn Git Branching](https://learngitbranching.js.org/) - Work on your version control skills at beginner or advanced level. (1 hour)
- :hatched_chick: [The seven rules of a great Git commit message](https://chris.beams.io/posts/git-commit/) - Write concise and consistent Git commit messages. (5 min)
- :snake: [Trunk Based Development](https://trunkbaseddevelopment.com/) - Use a simple branching approach that scales well to teams. (10 min)

### Code review

- :snake: [Google's "How to do a code review"](https://google.github.io/eng-practices/review/reviewer/) - Review code in a way your colleagues will love (Note: Change List ~= Pull Request). (30 min)
- :snake: [Code Health: Respectful Reviews == Useful Reviews](https://testing.googleblog.com/2019/11/code-health-respectful-reviews-useful.html) - Resolve code review comments respectfully. (5 min)

### Python patterns

- [The Definitive Guide to Python import Statements](https://chrisyeh96.github.io/2017/08/08/definitive-guide-python-imports.html) - Resolve common importing problems. (15 min)
- [PEP8 style guide, and why it is important](https://pragmaticcoders.com/blog/pep8-and-why-is-it-important/) - What PEPs are and what PEP8 is. (5 min)
- [PEP20 "The Zen of Python"](https://www.python.org/dev/peps/pep-0020/) - Get to know the guiding principles for Python's design. (1 min)
- [Python Design Patterns](https://python-patterns.guide) - High-level software engineering architecture patterns in Python. (30 min)
- [SOLID](https://en.wikipedia.org/wiki/SOLID) - High-level software engineering architecture principles. (30 min)
- [The Little Book of Python Anti-Patterns](https://docs.quantifiedcode.com/python-anti-patterns/) - Low-level Python idioms. (45 min)
- [Understanding Python's logging module](https://www.electricmonk.nl/log/2017/08/06/understanding-pythons-logging-module/) - Use the `logging` module effectively. (10 min)
- [Please fix your decorators](https://hynek.me/articles/decorators/) - Why you should probably use [`wrapt`](https://github.com/GrahamDumpleton/wrapt) to write your decorators. (10 min)
- [Effective Python](https://github.com/SigmaQuan/Better-Python-59-Ways/blob/master/README.md) - Apply 59 ways to write better Python (X hours)

### Linting

- [Flake8](http://flake8.pycqa.org/en/latest/manpage.html) - Enforce code style consistency in a Python project. (10 min) 
- [Flake8 extensions](https://github.com/DmytroLitvinov/awesome-flake8-extensions) - Pick the right Flake8 extensions.
- [Pylint](https://pylint.readthedocs.io/en/latest/)
- [pydocstyle](http://www.pydocstyle.org/en/4.0.1/index.html) - Check compliance with Python docstring conventions. (5 min)

### Testing

- [hypothesis-auto](https://timothycrosley.github.io/hypothesis-auto) - Write fully automatic unit tests based on type annotations. (30 min)

### Typing

- :hatched_chick: [Python Type Hints](https://kunigami.blog/2019/12/26/python-type-hints/) - How to apply both basic and advanced type hints. (5 min)
- :hatched_chick: [The state of type hints in Python](https://www.bernat.tech/the-state-of-type-hints-in-python/) - Why you should be using type hints. (5 min)
- :hatched_chick: [Leveraging type system to avoid mistakes](https://www.beyondthelines.net/programming/leveraging-the-type-system-to-avoid-mistakes/) - More motivation why you should be using type hints. (5 min)
- :unicorn: [Mypy protocols](https://mypy.readthedocs.io/en/latest/protocols.html) - Use advanced concepts such as Protocols. (15 min)
- :snake: [Pydantic overview](https://pydantic-docs.helpmanual.io/) - Stop writing `Dict[str, Any]` type hints and instead use `BaseModel`s. (10 min - 1 hour)
- :snake: [Enums](https://pydantic-docs.helpmanual.io/usage/types/#enums-and-choices) - Stop writing magic `str`s and instead use `Enum`s. (5 min)

## Machine Learning

### Practical theory

_While, in theory, you can just download Tensorflow and start making deep neural networks, it doesn’t hurt to know some of the theory and philosophy that lies behind the algorithms that so many of us know and love today._

- [Learning Machine Learning: An online comic from Google AI](http://cloud.google.com/products/ai/ml-comic-1) - Understand the basics of supervised and unsupervised learning. (15 min)
- [Rules of Machine Learning by Google](https://developers.google.com/machine-learning/guides/rules-of-ml)
- [Bias and variance](https://elitedatascience.com/bias-variance-tradeoff) - Distinguish between different types of prediction error. (5 min)
- [Bias and variance and the .632 rule](https://stats.stackexchange.com/questions/96739/what-is-the-632-rule-in-bootstrapping) - Balance bias and variance when bootstrapping. (10 min)
- [Generalization performance & model selection, nested cross-validation](https://stats.stackexchange.com/questions/64991/model-selection-and-cross-validation-the-right-way) - Use best practices for cross-validation. (10 min)
- [Stacking strategies with and without leaks](https://www.kaggle.com/general/18793) - Choose the right cross-validation strategy when stacking. (15 min)
- [Backpropagation is the chain rule to compute the gradient](https://ml-cheatsheet.readthedocs.io/en/latest/backpropagation.html) - Make the connection between backpropagation and the chain rule. (20 min)
- [Backprop is not just the chain rule](https://timvieira.github.io/blog/post/2017/08/18/backprop-is-not-just-the-chain-rule/) - Make the connection between backpropagation and Lagrange multipliers. (20 min)
- [You're all calculating churn rates wrong](https://catchjs.com/Blog/Churn) - Correctly define what churn is. (15 min)

### Pandas

- :snake: [Modern Pandas series (Part 1 - 7)](https://tomaugspurger.github.io/modern-1-intro.html) - Write idiomatic pandas. (1 hour)

### Sklearn

- [Custom Estimators](http://danielhnyk.cz/creating-your-own-estimator-scikit-learn/) - Create your own custom estimator (20 min)
- [Pipelines](http://scikit-learn.org/stable/modules/pipeline.html) - Combine transformers and estimators into pipelines (15 min)
- [Pipelines and custom Estimators](http://zacstewart.com/2014/08/05/pipelines-of-featureunions-of-pipelines.html)
- [Tuning hyperparameters](https://scikit-learn.org/stable/modules/grid_search.html) - Implement grid search and randomized search for parameter optimization. (10 min)

## DevOps

### Package management

- [Understanding Conda and Pip](https://www.anaconda.com/understanding-conda-and-pip/) - Know the advantages of Conda over Pip. (5 min)
- [Conda tutorial](https://geohackweek.github.io/Introductory/01-conda-tutorial/) - Manage packages and reproducible environments using one tool. (15 min)
- [Conda package index](https://www.anaconda.org/search) - Search for packages in Anaconda Cloud. (1 min)
- [Conda myths](http://jakevdp.github.io/blog/2016/08/25/conda-myths-and-misconceptions/) - Debunk some common myths and misconceptions about Conda. (5 min)
- [Conda in-depth](https://www.slideshare.net/AaronMeurer/conda-a-binary-scipy2014)

### Containerization

- [Docker getting started](https://docs.docker.com/get-started/)
- [Dockerfile best practices](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/) - Build efficient images (30 min)
- [Dockerizing Python is hard](https://pythonspeed.com/articles/dockerizing-python-is-hard/)
- [Multi-stage builds #3: Why your build is surprisingly slow, and how to speed it up](https://pythonspeed.com/articles/faster-multi-stage-builds/)
- [BuildKit Features You Might Want to Know About](https://vsupalov.com/docker-buildkit-features/)

### Shell

- [ShellHarden & ShellCheck](https://github.com/anordal/shellharden/blob/master/how_to_do_things_safely_in_bash.md)
- [Your terminal is not a terminal: An Introduction to Streams](https://lucasfcosta.com/2019/04/07/streams-introduction.html)

### Terraform

- [Terraform best practices](https://github.com/BWITS/terraform-best-practices)

### Infrastructure

- [ZeroMQ: a socket library with message queue primitives](https://learning-0mq-with-pyzmq.readthedocs.io/en/latest/pyzmq/patterns/pair.html)
- [Redis: a key-value store with optional persistence](https://github.com/leohowell/redis-lru)
- [RabbitMQ: a message queue library with persistance](https://www.rabbitmq.com/tutorials/tutorial-one-python.html)
- [Kafka is the opposite of RabbitMQ with "smart consumers" and a "dumb broker"](https://blog.usejournal.com/getting-started-with-kafka-5004c0a734c3)
- [What Every Software Engineer Should Know about Apache Kafka](https://www.michael-noll.com/blog/2020/01/16/what-every-software-engineer-should-know-about-apache-kafka-fundamentals/)

## Related awesome lists

- [The Missing Semester of Your CS Education](https://missing.csail.mit.edu/) - A collection of skills that are often expected to be self-taught.
- [A Survey of Deep Learning for Scientific Discovery](https://arxiv.org/abs/2003.11755) - An overview of Deep Learning tasks and approaches.

## To add

- TODO: Mypy strict mode.
- TODO: Raymond Hettinger
- TODO: Gridsearch vs random search vs Bayesian hyperparam optimization (gaussian processes)
- TODO: Comparison of bayesian hyperparam optimizers (PyGPGO)
- TODO: conda vs virtualenv, pyenv, pipenv.
- TODO: explain how conda-forge works.
- TODO: explain registries (Docker Hub, ECR, GitLab)
- TODO: explain environment.yml + interactions with Docker.
- TODO: S3, DynamoDB, MongoDB
- TODO: CVE scans (frontend and backend)
- TODO: OSS license scan
- TODO: mutual TLS, IP whitelisting, (VPN)
- TODO: Kinesis streams
- TODO: Linting built-in to Terraform with `-check`.
- TODO: Tech in our pure cookiecutter scaffolding.
- TODO: Cherry picking?
- TODO: MLOps
- TODO: KISS

## Curated by Radix

[Radix](https://radix.ai) is a Belgium-based Machine Learning company.

We invent, design and develop AI-powered software. Together with our clients, we identify which problems within organizations can be solved with AI, demonstrating the value of Artificial Intelligence for each problem.

Our team is constantly looking for novel and better-performing solutions and we challenge each other to come up with the best ideas for our clients and our company.

Here are some examples of what we do with Machine Learning, the technology behind AI:
- Help job seekers find great jobs that match their expectations. On the [Belgian Public Employment Service website](https://www.vdab.be), you can find our job recommendations based on your CV alone.
- Help hospitals save time. We extract diagnosis from patient discharge letters.
- Help publishers estimate their impact by detecting copycat articles.

We work hard and we have fun together. We foster a culture of collaboration, where each team member feels supported when taking on a challenge, and trusted when taking on responsibility.

<img width="135" src="https://radix-ai-static-assets.s3-accelerate.amazonaws.com/radix_logo_with_baseline@2x.png" alt="radix">
