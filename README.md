# Getting Started With Testing in Python

## What we will learn

- [ ] How to create a basic test;
- [ ] Execute it;
- [ ] Find the bugs before your users do;
- [ ] About the tools available to write and execute tests ;
- [ ] Check your application’s performance, and even look for security issues.

## How to Structure a Simple Test

[Writing Your First Test](https://realpython.com/python-testing/)
Before you dive into writing tests, you’ll want to first make a couple of decisions:

1. What do you want to test?
2. Are you writing a unit test or an integration test?

Then the structure of a test should loosely follow this workflow:

1. Create your inputs
2. Execute the code being tested, capturing the output
3. Compare the output with an expected result

## How to Write Assertions

[Writing Your First Test](https://realpython.com/python-testing/)
The last step of writing a test is to validate the output against a known response. This is known as an assertion.
There are some general best practices around how to write assertions:

- Make sure tests are repeatable and run your test multiple times to make sure it gives the same result every time
- Try and assert results that relate to your input data, such as checking that the result is the actual sum of values in the sum() example

### References

1. [Getting Started With Testing in Python](https://realpython.com/python-testing/)
2. [unittest - Unit Testing Framework](https://docs.python.org/3/library/unittest.html)
3. [Nose 2 Documentation](https://docs.nose2.io/en/latest/)
4. [PyTest Documentation](https://docs.pytest.org/en/latest/)