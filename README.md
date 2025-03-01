# Disclaimer
Sharing is caring! This is part of a learning journey. We are much more curious individuals than experts. The objective is to share our learnings so far while enabling us to collaborate, learn and connect around an important topic. We assume that independently of your experience, you are curious to learn, courageous to ask and share and, finally, respectful about the stage each one is in right now.

# Purpose
Dive into tests and Test-Driven-Development (TDD) by sharing experience and practicing together
- Practical workshop, mainly with examples
- Think programming as communicating 
  * Simple, clear, robust code
  * Maintainable, scalable, understandable
  * Effective, resilient to change

# Community
In Slack: [#tdd-test-driven-development](https://app.slack.com/client/T02JL00JU/C01SP39JDFU/thread/C8W3SUK17-1622572475.035100).

# Why tests?
- Make sure the code works as expected
- Detect edge cases
- Feel confident to refactor without being afraid of breaking the entire pipeline
- Your teammates can understand your
functions by looking at your tests
- Prevent unexpected output
- Simplifies updating code
- Increases overall efficiency of developing code
- And most importantly prevents you from pushing any broken code into production!

# Requirements
Please check the [dedicated page for this workshop](/docs/workshop-pre-reqs.md).

# Story
Disclaimer: the workshop is based on our own work together.
You will find imperfections or questionable things, let's discuss them.

We will go through:
1. Check that all requirements are in place for all
2. Share previous experiences with TDD
3. Demonstrate TDD while working together (~peer-programming)
4. Present a problem to solve
5. After each step, a pause for:
    - sharing the work
    - discussing key topics/challenges
    - catching up
6. Conclude with wrap-up and feedback

Commit early and often!
Good practices for a commit, by [Chris Beams](https://chris.beams.io/posts/git-commit/)

# One way to go
0. Make a list of tests we know we need to have working
1. Add a little test: write just enough of a test to fail
2. Run all tests and fail
3. Make a little change: write just enough code to make it pass
4. Run the tests and succeed
5. Refactor to remove duplication: clean up the mess made getting the test to pass

Discussions:
- Being able to take teeny-tiny steps, not necessarily doing it
- Add items to our to-do list rather than addressing them all at once
- Commit early and often!
- Let's try: Test pipeline, continuous integration
- Remember to save changes :-) 
- DRY: Don't Repeat Yourself!
- @pytest.mark.parametrize to run multiple test cases
- Debugging with test (tools?)

# Contributing

## Run tests
[pytest](https://docs.pytest.org/en/latest/) is used as the test runner, to test:

```sh
# Test
pytest
```

this requires that the dev dependencies from `dev-requirements.txt` are installed.

```sh
# Install test requirements
pip install -r dev-requirements.txt
```

# References
The exercise presented on the issues are based on: https://kata-log.rocks/string-calculator-kata
