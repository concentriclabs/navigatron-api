
# Asynchronous NAVIGATRON Programming Interface (API)
![[](https://www.youracclaim.com/org/ibm/badge/cognitive-services-data-scientist)](https://storage.googleapis.com/bhe-drakkar-team/Data_Scientist_Badge.png)
![[](https://www.youracclaim.com/org/rmit-university/badge/ai-programming-with-python)](https://storage.googleapis.com/bhe-drakkar-team/AI-Programming-Badge.png)

<hr />

# Overview
This app is the video game (kk) === "- Simple structure for real use to serve models in high risk operations, validated and built by the Drakkar do Brasil MLOps engineering team, reference in the Data / AI universe, in the Brazil and the world "-
.
The models === (the game cartridges).

They can be developed to taste, to simulate any world in NAVIGATRON.
Best door simulation game in the world.

# Architecture Design

> TODO Description

![](https://storage.googleapis.com/bhe-drakkar-team/arqt-api-ml.png)
# Challenge

[Abertura Brasil Hack Export](https://youtu.be/kRC6m_qR3OQ)

[INNOVATION PROJECT BRASIL EXPORT 2020](https://storage.googleapis.com/bhe-drakkar-team/solution-idea-analytics-202011171230.pdf)

Exploratory Data Analysis (EDA): [pending*](#)

# What's new?

**MVP-v1.0.0** released!

<!-- **v1.0.0** released! -->

# Table of contents

- [Architecture Design](#Overview)
- [What's new?](#whats-new)
- [Table of contents](#table-of-contents)
- [Development](#development)
    - [Dependencies](#dependencies)
    - [Project content](#project-content)
- [Contribute](#contribute)
    - [Contributors ✨](#contributors-)
- [License](#mit-license)

# Development
🤯 let's go horse despaired process 😭

## Dependencies
[(Back to top)](#table-of-contents)

**Docker**

Docker is a set of platform as a service products that use OS-level virtualization to deliver 
software in packages called containers. Containers are isolated from one another and bundle 
their own software, libraries and configuration files.

- [Get Docker](https://docs.docker.com/get-docker/)

Run:

> 1 [TODO Description]
```
$ docker build -t navigatron-flask-app .
```
> 2 [TODO Description]
```
$ docker run -e FLASK_APP=models_realtime_batch.py navigatron-flask-app -m flask routes
```
> 3 [TODO Description]
```
$ docker run -e FLASK_APP=models_realtime_batch.py -e FLASK_ENV=development -p 5000:5000 navigatron-flask-app
```
> 4 [TODO Description]
```
$ docker run -e FLASK_APP=models_realtime_batch.py -e FLASK_ENV=development -p 5000:5000 navigatron-flask-app -m flask run --host 0.0.0.0
```
> 5 [TODO Description]
```
$ docker logs $(docker ps --filter ancestor=navigatron-flask-app -q) --follow
```
> 6 [TODO Description]
```
$ docker run -it --entrypoint='' navigatron-flask-app /bin/sh
```

### Project content
[(Back to top)](#table-of-contents)

> TODO

# Contribute
[(Back to top)](#table-of-contents)

### Contributors ✨

<table>
  <tr>
    <td align="center"><a href="https://github.com/fermaiasoares"><img src="https://avatars1.githubusercontent.com/u/8242323?s=460&u=32bf38286aae43074b5c70f3998906c7f9f96339&v=4" width="100px;" alt=""/><br /><sub><b>Fernando Maia </b></sub></a><br />
    <small>Tech Lead Developer
Front-End</small>
</td>
      <td align="center"><a href="https://github.com/LeandroRamalho"><img src="https://avatars.githubusercontent.com/u/38744016?s=460&u=dfdde0cce7b5188457e693b3438dd11a7cded2ae&v=4" width="100px;" alt=""/><br /><sub><b>Leandro Ramalho </b></sub></a><br />
    <small>UI/UX Designer Specialist</small>
  </td>
  <td align="center"><a href="https://github.com/fernandozoomp"><img src="https://avatars2.githubusercontent.com/u/64983541?s=460&u=1c399b32f2a9044ef944b620d04e77f0452c9388&v=4" width="100px;" alt=""/><br /><sub><b>Fernando Cardoso </b></sub></a><br />
    <small>Senior Back-End Developer</small>
    </td>
      <td align="center"><a href="https://github.com/henriquehsilva"><img src="https://avatars3.githubusercontent.com/u/40860601?s=460&u=a31035b210c308987ec3830019186abbab646a00&v=4" width="100px;" alt=""/><br /><sub><b>Henrique Silva </b></sub></a><br />
    <small>Project Manager</small>
    </td>
    </td>
      <td align="center"><a href="#"><img src="https://avatars2.githubusercontent.com/u/7357119?s=460&u=21625b861afde168416b8651cec693faec2c204e&v=4" width="100px;" alt=""/><br /><sub><b>Rafael IBO </b></sub></a><br />
    <small>AI Specialist Developer</small>
    </td>
  </tr>
</table>

<br />

# MIT License
[(Back to top)](#table-of-contents)

Copyright (c) 2020 Drakkar Team

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
