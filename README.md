<p align="center"><img src="/misc/travis-ci.gif"><img src="/misc/github.gif" height=325 width=375></p>

---

<p align="center">
  <img src="https://img.shields.io/travis/ajaymache/travis-ci-with-github.svg">&nbsp;&nbsp;&nbsp;
  <img src="https://img.shields.io/github/license/ajaymache/travis-ci-with-github.svg">&nbsp;&nbsp;&nbsp;
  <img src="https://img.shields.io/github/issues/ajaymache/travis-ci-with-github.svg?colorB=DAA520">&nbsp;&nbsp;&nbsp;
  <img src="https://img.shields.io/github/languages/count/ajaymache/travis-ci-with-github.svg?colorB=ff5733">&nbsp;&nbsp;&nbsp;
  <img src="/shields/contributions.svg">
</p>

---

### About
This repository aims at getting started with **[Travis CI](https://travis-ci.org)** for your **[Github](https://github.com)** repositories. For demonstration purposes a very simple package is created with some test cases to explain how to integrate **Travis CI** for continous integration with **Github**.

### What is Travis CI?
Travis CI is a hosted, distributed continuous integration service used to build and test software projects hosted at GitHub.
Open source projects may be tested at no charge via [https://travis-ci.org](https://travis-ci.org). Private projects may be tested at [https://travis-ci.com](https://travis-ci.com) on a fee basis. TravisPro provides custom deployments of a proprietary version on the customer's own hardware. (**Source** - [Wikipedia](https://en.wikipedia.org/wiki/Travis_CI))

### Getting started
- The folder **pkg** contains a arithmetic package which has been created for demonstration puposes. The folder **pkg** has 2 sub-folders **arithmetic** and **testing** with files **arithmetic.py** and **testing.py**.
- The **arithmetic.py** file is a simple module to do arithmetic operations like addition, subtraction, multiplication and division. The **testing.py** file is another simple module which runs some testcases on the package.
- To successfully integrate **Travis CI** with your **Github** repository you will need:
  1. 
