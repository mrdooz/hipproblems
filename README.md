# Hipmunk Problems
This is a collection of (simplified) problems that we face at Hipmunk.

- [Building a Flight Search API](https://github.com/Hipmunk/hipproblems/tree/master/searchrunner)
- [Implementing a Distributed Work Queue](https://github.com/Hipmunk/hipproblems/tree/master/workqueue)

# Installation

*Assumes you're using Python 2.7*

1. `git clone https://github.com/Hipmunk/hipproblems.git`
2. `cd hipproblems`
3. `python setup.py develop`

If the setup script fails make sure you have [setuptools](https://pypi.python.org/pypi/setuptools) installed and try again.

Note, the work queue requires a [Redis](http://redis.io/) server.