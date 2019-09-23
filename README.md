# Awesome Full Stack Machine Learning

<div align="center">
	<img width="500" height="350" src="https://github.com/sindresorhus/awesome/raw/master/media/logo.svg?sanitize=true" alt="Awesome">
  
  A curated list of delightful Machine Learning Engineering resources. <br>
  The resources are structured as follows: *Title* - *Description* (*Reading time*) <br> The descriptions are written so that they complete the sentence *"After reading this article you will have learned to ..."*.
  
  For more awesomeness, check out [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome).

</div>

## Contents

- [Communication](#communication)
- [Software Engineering](#software-engineering)
  - [API design](#api-design)
  - [Version control](#version-control)
  - [Code review](#code-review)
  - [Python](#python)
    - [Ideology](#ideology)
    - [Logging](#logging)
    - [Linting](#linting)
    - [Testing](#testing)
    - [Type annotation](#type-annotation)
- [Machine Learning](#machine-learning)
  - [Practical Theory](#practical-theory)
  - [Sklearn](#sklearn)
- [DevOps](#devops)
  - [Package management](#package-management)
  - [Containerization](#containerization)
  - [Shell](#shell)
  - [Terraform](#terraform)
  - [Security](#security)
  - [Infrastructure](#infrastructure)
    - [Datastores](#datastores)
    - [Message queues](#message-queues)

## Communication

- [BLUF: The Military Standard](https://www.animalz.co/blog/bottom-line-up-front/) - Make your emails and communication more powerful. (5 min)
- [The XY problem](http://xyproblem.info/) - Focus on the solution when asking for help. (5 min)
- [MECE lists](https://www.oreilly.com/ideas/a-foundational-strategy-pattern-for-analysis-mece) - Write structured lists for documents, slides, and Slack. (10 min)
- [Nonviolent communication](https://medium.com/s/please-advise/the-essential-guide-to-difficult-conversations-41f736e63ccf) - Deliver constructive feedback in difficult situations. (10 min)
- [SMART goals](https://en.wikipedia.org/wiki/SMART_criteria) - Define goals in a structured way. (5 min)
- [The Halo effect](https://effectiviology.com/halo-effect/) - Account for the cognitive bias that might influence the way you view others. (10 min)
- [SCQA/SCoRE stories and NOSE/SPIN sales pitches](http://jchyip.blogspot.com/2011/11/good-message-structure-underlies-all.html) - Structure presentations, proposals and sales interactions. (5 min)
- [E-mail like a boss](https://images.app.goo.gl/KZtSNj8n7xxCLrGZ7) - Write useful e-mail phrases. (1 min)

## Software Engineering

### API design

- [FastAPI docs](https://fastapi.tiangolo.com/tutorial/first-steps/) - Build RESTful APIs that correspond one-to-one with the OpenAPI spec. (1 hour)
- [Zalando's RESTful API guidelines](https://opensource.zalando.com/restful-api-guidelines/)
- [gRPC compared to REST](https://eng.fromatob.com/post/2019/05/why-were-switching-to-grpc/) - Compare the two leading solutions for communication between services. (5 min)
- [Terrifically Simple JSON](https://github.com/mpnally/Terrifically-Simple-JSON) - Represent data using JSON. (10 min)
- [HTTP response headers for the responsible developer](https://www.twilio.com/blog/a-http-headers-for-the-responsible-developer) - Improve user experience using HTTP headers. (2 min)
- [Falsehoods programmers believe about time](http://infiniteundo.com/post/25326999628/falsehoods-programmers-believe-about-time) - Avoid most of the assumptions made about time. (2 min)
- [Falsehoods programmers believe about names](https://www.kalzumeus.com/2010/06/17/falsehoods-programmers-believe-about-names/) - Avoid most of the assumptions made about personal names. (5 min)
- [Semantic versioning](https://semver.org/) - Assign and increment version numbers of projects. (10 min)

### Version control

- [Learn Git Branching](https://learngitbranching.js.org/) - Work on your version control skills at beginner or advanced level. (10 min and more)
- [The seven rules of a great Git commit message](https://chris.beams.io/posts/git-commit/) - Write concise and consistent Git commit messages. (10 min)

### Code review

- [Google's "How to do a code review"](https://google.github.io/eng-practices/review/reviewer/) - How to code reviews your colleages will love. (20 min)

### Python

#### Ideology

- [The Definitive Guide to Python import Statements](https://chrisyeh96.github.io/2017/08/08/definitive-guide-python-imports.html) - Resolve common importing problems. (15 min)
- [PEP20 "The Zen of Python"](https://www.python.org/dev/peps/pep-0020/) - Get to know the guiding principles for Python's design. (1 min)
- [PEP8, and why it is important](https://pragmaticcoders.com/blog/pep8-and-why-is-it-important/) - Write consistent code with high readability. (5 min)
- [Python patterns](https://python-patterns.guide)
- TODO: Raymond Hettinger

#### Logging

- [Logging best practices and gotchas](https://www.electricmonk.nl/log/2017/08/06/understanding-pythons-logging-module/) - Understand the `logging` module. (10 min)

#### Linting

- [Flake8](http://flake8.pycqa.org/en/latest/manpage.html) - Enforce code style consistency in a Python project. (10 min) 
- TODO: extensions of flake8 (sub-bullets)
- [Pylint](https://pylint.readthedocs.io/en/latest/)
- [pydocstyle](http://www.pydocstyle.org/en/4.0.1/index.html) - Check compliance with Python docstring conventions. (5 min)

#### Testing

- [hypothesis-auto](https://timothycrosley.github.io/hypothesis-auto) - Write fully automatic unit tests based on type annotations. (30 min)

#### Type annotation

- [Getting started with Mypy](https://mypy.readthedocs.io/en/stable/getting_started.html)
- [Leveraging type system to avoid mistakes](https://www.beyondthelines.net/programming/leveraging-the-type-system-to-avoid-mistakes/)
- [Mypy protocols](https://mypy.readthedocs.io/en/latest/protocols.html)
- [Facebook's type checker Pyre](https://pyre-check.org/)
- TODO: Mypy strict mode.

## Machine Learning

### Practical Theory

_While, in theory, you can just download Tensorflow and start making deep neural networks, it doesn’t hurt to know some of the theory and philosophy that lies behind the algorithms that so many of us know and love today._

- [Learning Machine Learning: An online comic from Google AI](http://cloud.google.com/products/ai/ml-comic-1) - Understand the basics of supervised and unsupervised learning. (15 min)
- [Bias and variance](https://elitedatascience.com/bias-variance-tradeoff) - Distinguish between different types of prediction error. (5 min)
- [Bias and variance and the .632 rule](https://stats.stackexchange.com/questions/96739/what-is-the-632-rule-in-bootstrapping) - Balance bias and variance when bootstrapping. (10 min)
- [Generalization performance & model selection, nested cross-validation](https://stats.stackexchange.com/questions/64991/model-selection-and-cross-validation-the-right-way) - Use best practices for cross-validation. (10 min)
- [Stacking strategies with and without leaks](https://www.kaggle.com/general/18793) - Choose the right cross-validation strategy when stacking. (15 min)
- [Backpropagation is the chain rule to compute the gradient](https://ml-cheatsheet.readthedocs.io/en/latest/backpropagation.html) - Make the connection between backpropagation and the chain rule. (20 min)
- [Backprop is not just the chain rule](https://timvieira.github.io/blog/post/2017/08/18/backprop-is-not-just-the-chain-rule/) - Make the connection between backpropagation and Lagrange multipliers. (20 min)


### Sklearn

- [Custom Estimators](http://danielhnyk.cz/creating-your-own-estimator-scikit-learn/) - Create your own custom estimator (20 min)
- [Pipelines](http://scikit-learn.org/stable/modules/pipeline.html) - Combine transformers and estimators into pipelines (15 min)
- [Pipelines and custom Estimators](http://zacstewart.com/2014/08/05/pipelines-of-featureunions-of-pipelines.html)
- [Tuning hyperparameters](https://scikit-learn.org/stable/modules/grid_search.html) - Implement grid search and randomized search for parameter optimization. (10 min)
- TODO: Gridsearch vs random search vs Bayesian hyperparam optimization (gaussian processes)
- TODO: Comparison of bayesian hyperparam optimizers (PyGPGO)

## DevOps

### Package management

- [Conda tutorial](https://geohackweek.github.io/Introductory/01-conda-tutorial/) - Manage packages and reproducible environments using one tool. (15 min)
- [Conda package index](https://www.anaconda.org/search) - Search for packages in Anaconda Cloud. (1 min)
- [Conda myths](http://jakevdp.github.io/blog/2016/08/25/conda-myths-and-misconceptions/) - Debunk some common myths and misconceptions about Conda. (5 min)
- [Conda in-depth](https://www.slideshare.net/AaronMeurer/conda-a-binary-scipy2014)
- TODO: conda vs virtualenv, pyenv, pipenv.
- TODO: explain how conda-forge works.
- TODO: explain environment.yml + interactions with Docker.

### Containerization

- [Docker getting started](https://docs.docker.com/get-started/)
- [Dockerfile best practices](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/) - Build efficient images (30 min)
- [Dockerizing python is hard](https://pythonspeed.com/articles/dockerizing-python-is-hard/)
- TODO: explain registries (Docker Hub, ECR, GitLab)

### Shell

- [ShellHarden & ShellCheck](https://github.com/anordal/shellharden/blob/master/how_to_do_things_safely_in_bash.md)
- [Your terminal is not a terminal: An Introduction to Streams](https://lucasfcosta.com/2019/04/07/streams-introduction.html)

### Terraform

- [Terraform best practices](https://github.com/BWITS/terraform-best-practices)
- TODO: Linting built-in to Terraform with `-check`.

### Security

- TODO: CVE scans (frontend and backend)
- TODO: OSS license scan
- TODO: mutual TLS, IP whitelisting, (VPN)

### Infrastructure

#### Datastores

- TODO: S3
- TODO: DynamoDB
- TODO: MongoDB

#### Message queues

- [ZeroMQ: a socket library with message queue primitives](https://learning-0mq-with-pyzmq.readthedocs.io/en/latest/pyzmq/patterns/pair.html)
- [Redis: a key-value store with optional persistence](https://github.com/leohowell/redis-lru)
- [RabbitMQ: a message queue library with persistance](https://www.rabbitmq.com/tutorials/tutorial-one-python.html)
- TODO: Kafka is the opposite of RabbitMQ with "smart consumers" and a "dumb broker"
- TODO: Kinesis streams

## Developed by radix.ai

At [radix.ai](https://radix.ai/), we invent, design and develop AI-powered software.

Here are some examples of what we do with Machine Learning, the technology behind AI:
- Help job seekers find a job. On the [Belgian Public Employment Service website](https://www.vdab.be/), we serve job recommendations based on your CV.
- Help hospitals save time. We extract diagnoses from patient discharge letters.
- Help publishers calculate their impact, by detecting copycat articles.

You can follow our adventures on [medium](https://medium.com/radix-ai-blog).
