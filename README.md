# Full stack Machine Learning

## Reproducibility

### Package management

Conda tutorial
https://geohackweek.github.io/Introductory/01-conda-tutorial/

Conda package index
https://www.anaconda.org

Conda myths
http://jakevdp.github.io/blog/2016/08/25/conda-myths-and-misconceptions/

Conda in-depth
https://www.slideshare.net/AaronMeurer/conda-a-binary-scipy2014

### Containerization

Docker getting started
https://docs.docker.com/get-started/

Dockerfile best practices
https://docs.docker.com/develop/develop-images/dockerfile_best-practices/

## Software Engineering

### Git

Learn git interactively https://learngitbranching.js.org/

### Meta

Semantic Versioning https://semver.org/

### Message queues

- Learn about ZeroMQ (which is a socket library with message queue primitives) and messaging patterns with https://learning-0mq-with-pyzmq.readthedocs.io/en/latest/pyzmq/patterns/pair.html
- Redis is a key-value store with persistence if you want it, and recently some message queue like features. But it's still mainly a key-value store. One nice use case is a redis-backed LRU-cache: https://github.com/leohowell/redis-lru.
- RabbitMQ is a message queue library at heart, with persistence options that aren't bolted on like with Redis. See for example: https://www.rabbitmq.com/tutorials/tutorial-one-python.html. It's two main message queue abstractions are "pub-sub" and the "competing consumers" model.
- Kafka is kind of like RabbitMQ but focuses on processing of streaming data by having "smart consumers" and a "dumb broker". RabbitMQ is the reverse of that. Kafka runs on the JVM, so it's a pretty heavy dependency.

### Python

#### Programming patterns

Python patterns https://python-patterns.guide

#### Logging

Logging best practices and gotchas https://www.electricmonk.nl/log/2017/08/06/understanding-pythons-logging-module/

#### Type annotations

Static type checking with mypy http://mypy-lang.org/

Static type checking with pyre https://pyre-check.org/

Leveraging type system to avoid mistakes https://www.beyondthelines.net/programming/leveraging-the-type-system-to-avoid-mistakes/

## Machine Learning

### Generalization performance

Bias and variance and the .632 rule https://stats.stackexchange.com/questions/96739/what-is-the-632-rule-in-bootstrapping

Generalization performance & model selection, nested cross-validation https://stats.stackexchange.com/questions/64991/model-selection-and-cross-validation-the-right-way

### Sklearn

Estimators, Transformers http://scikit-learn.org/dev/developers/contributing.html#apis-of-scikit-learn-objects

Custom Estimators http://danielhnyk.cz/creating-your-own-estimator-scikit-learn/

Pipelines http://scikit-learn.org/stable/modules/pipeline.html

Pipelines and custom Estimators http://zacstewart.com/2014/08/05/pipelines-of-featureunions-of-pipelines.html

## DevOps

### Shell

ShellHarden & ShellCheck https://github.com/anordal/shellharden/blob/master/how_to_do_things_safely_in_bash.md

### Terraform

Terraform best practices https://github.com/BWITS/terraform-best-practices
