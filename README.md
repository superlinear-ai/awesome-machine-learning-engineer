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
  - [Python](#python)
    - [Ideology](#ideology)
    - [Logging](#logging)
    - [Linting](#linting)  
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

- [The XY problem](http://xyproblem.info/) - Focus on the solution when asking for help. (5 min)
- [MECE lists](https://www.oreilly.com/ideas/a-foundational-strategy-pattern-for-analysis-mece) - Write structured lists for documents, slides, and Slack. (10 min)
- [Nonviolent communication](https://medium.com/s/please-advise/the-essential-guide-to-difficult-conversations-41f736e63ccf) - Deliver constructive feedback in difficult situations. (10 min)
- [SMART goals](https://en.wikipedia.org/wiki/SMART_criteria) - Define goals in a structured way. (5 min)
- [The Halo effect](https://effectiviology.com/halo-effect/) - Account for the cognitive bias that might influence the way you view others. (10 min)
- [SCQA/SCoRE stories and NOSE/SPIN sales pitches](http://jchyip.blogspot.com/2011/11/good-message-structure-underlies-all.html) - Structure presentations, proposals and sales interactions. (5 min)
- [E-mail like a boss](https://images.app.goo.gl/KZtSNj8n7xxCLrGZ7) - Write useful e-mail phrases. (1 min)

## Software Engineering

### API design

- [Zalando's RESTful API guidelines](https://opensource.zalando.com/restful-api-guidelines/)
- [gRPC compared to REST](https://eng.fromatob.com/post/2019/05/why-were-switching-to-grpc/)
- [Terrifically Simple JSON](https://github.com/mpnally/Terrifically-Simple-JSON)
- [HTTP response headers for the responsible developer](https://www.twilio.com/blog/a-http-headers-for-the-responsible-developer)
- [Falsehoods programmers believe about time](http://infiniteundo.com/post/25326999628/falsehoods-programmers-believe-about-time)
- [Falsehoods programmers believe about names](https://www.kalzumeus.com/2010/06/17/falsehoods-programmers-believe-about-names/)
- [Semantic versioning](https://semver.org/)

### Version control

- [Learn git interactively](https://learngitbranching.js.org/)
- [The seven rules of a great Git commit message](https://chris.beams.io/posts/git-commit/)

### Python

#### Ideology

- [The Definitive Guide to Python import Statements](https://chrisyeh96.github.io/2017/08/08/definitive-guide-python-imports.html)
- [Python's development is conducted through Python Enhancement Proposals (PEP)](https://en.wikipedia.org/wiki/Python_(programming_language)#Development)
- [PEP20 "The Zen of Python" is Python's ideology](https://www.python.org/dev/peps/pep-0020/)
- [PEP8 "Style Guide for Python Code" is a guide to writing idiomatic Python](https://www.python.org/dev/peps/pep-0008/)
- [Python patterns](https://python-patterns.guide)
- TODO: Raymond Hettinger

#### Logging

- [Logging best practices and gotchas](https://www.electricmonk.nl/log/2017/08/06/understanding-pythons-logging-module/)

#### Linting

- TODO: flake8 + extensions (sub-bullets)
- TODO: pylint
- TODO: pydocstyle

#### Type annotation

- [Getting started with Mypy](https://mypy.readthedocs.io/en/stable/getting_started.html)
- [Leveraging type system to avoid mistakes](https://www.beyondthelines.net/programming/leveraging-the-type-system-to-avoid-mistakes/)
- [Mypy protocols](https://mypy.readthedocs.io/en/latest/protocols.html)
- [Facebook's type checker Pyre](https://pyre-check.org/)
- TODO: Mypy strict mode.

## Machine Learning

### Practical Theory

- [Bias and variance and the .632 rule](https://stats.stackexchange.com/questions/96739/what-is-the-632-rule-in-bootstrapping)
- [Generalization performance & model selection, nested cross-validation](https://stats.stackexchange.com/questions/64991/model-selection-and-cross-validation-the-right-way)
- [Stacking strategies with and without leaks](https://www.kaggle.com/general/18793)
- [Backprop is not just the chain rule](https://timvieira.github.io/blog/post/2017/08/18/backprop-is-not-just-the-chain-rule/)
- [Backpropagation is the chain rule to compute the gradient](https://ml-cheatsheet.readthedocs.io/en/latest/backpropagation.html)

### Sklearn

- [Estimators vs. Transformers](http://scikit-learn.org/dev/developers/contributing.html#apis-of-scikit-learn-objects)
- [Custom Estimators](http://danielhnyk.cz/creating-your-own-estimator-scikit-learn/)
- [Pipelines](http://scikit-learn.org/stable/modules/pipeline.html)
- [Pipelines and custom Estimators](http://zacstewart.com/2014/08/05/pipelines-of-featureunions-of-pipelines.html)
- TODO: Gridsearch vs random search vs Bayesian hyperparam optimization (gaussian processes)
- TODO: Comparison of bayesian hyperparam optimizers (PyGPGO)

## DevOps

### Package management

- [Conda tutorial](https://geohackweek.github.io/Introductory/01-conda-tutorial/)
- [Conda package index](https://www.anaconda.org)
- [Conda myths](http://jakevdp.github.io/blog/2016/08/25/conda-myths-and-misconceptions/)
- [Conda in-depth](https://www.slideshare.net/AaronMeurer/conda-a-binary-scipy2014)
- TODO: conda vs virtualenv, pyenv, pipenv.
- TODO: explain how conda-forge works.
- TODO: explain environment.yml + interactions with Docker.

### Containerization

- [Docker getting started](https://docs.docker.com/get-started/)
- [Dockerfile best practices](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/)
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
