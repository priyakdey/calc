# Calculator

---

This project is a basic mathematical calculator which shows the use of 
[pytest](https://docs.pytest.org/en/stable/) to write unit test cases.


TDD or Test Driven Development is a widely used and proved technique for better code
quality and almost bug free code. When working with Python, we have a couple of options
and also can use unittest module which is inbuilt and distributed with the standard Python
binary.

But here, we are going to use pytest, which is a wrapper around the inbuilt module and helps
by removing a lot of boiler plat code.

This project is for my blog post to write about how to use Pytest and follow TDD and 
some other techniques used in testing like mocking and checking code coverage.


For Project Structure I am following  [Kenneth Reitz recommended in 2013](https://kennethreitz.org/essays/2013/01/27/repository-structure-and-python).
The source code goes under calc folder, the test cases goes under tests/ (I like to have separate sub-folders
for unit and non-unit test cases). Any documentation goes under docs/ (specially if you are writing a tool
or library, documentation does help in that).