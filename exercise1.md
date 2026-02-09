For a language like python, some of the common steps needed to implement CI includes linting, testing, building, and executing the CI runner. Before deploying our project to the end user, linting helps us finding and elimination syntax and styling errors. Lint helps ensure that we are following specific standards and best practice. To enforce these coding styles, we can use library like Pylint, Flake8, with Pylint being the most common choice among developers.

On the other hand, for testing, writting unit tests can be implemented with Pytest library. Pytest library is the standard test runner in python due to its ease of use.

In order to share a distributable packge of Python code we would need to build the project into .whl file format. To do this, python uses setuptools as the foundational library for packaging python projects. The tool can create a python package with a given pyproject.toml file.

Finally, when it comes to CI automation, we can use cloud based Github Action service, or locally implemented Jenkins pipeline. Jenkins is harder to setup compare to Github Actions, but it gives more flexiblity and control to the end user on how to specifically setup their own CI/CD pipeline. Github Action is also a popular method, comparing to Jenkins it is easier to setup, without the need of learning Jenkin's own domain specific language to implement the CI process.
