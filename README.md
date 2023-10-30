# ECE444-F2023-Lab5
Repo following Example: https://github.com/mjhea0/flaskr-tdd

# Lab 5 Unit Test Contributions
Unit Tests created by Bilal Ikram - test_correct_event_submission, test_duplicate_event_name_submission
Link to contributions: https://github.com/ECE444-2023Fall/project-1-web-application-design-group17-jigglies/blob/6e4cc5a29df1a1a8bdae58c46ed1885c185123cb/tests/app_test.py#L92-L131

# Advantages and Disadvantages of TDD (Test Driven Development)
TDD or Test Driven Development is a method of software development, where tests are written prior to the code being written. This can be advantageous as it means that you will only write code you need. When developing a large application it can be very easy to get side tracked and end up developing unneeded features. But with TDD, The code you write is the simplest code possible as it's all the code needed to implement the feature. Furthermore, the code is also easy to maintain as TDD promotes a Modular design. Since you are focused on individual unit tests, code becomes modular and makes maintenance much easier as features can be updated or replaced without impact on other parts of the system. TDD will also promote a High Test Coverage since each piece of code will have a corresponding test. This will also significantly reduce debugging as you are constantly testing the code as you write it.

Some disadvantages of TDD are that it can lead to a much slower Development Process. Especially for those new to TDD, the process can seem slower as you're writing tests before the actual code and adding a new step to development. Furthermore, TDD is only effective when implemented by the entire team, and since it can be hard to adopt, some members may not want to adopt TDD. This means that TDD will not be effective as it is only effective when an entire project follows it. Lastly TDD can lead to a much larger maintenance overhead. Just like the codebase, tests also need maintenance. As requirements evolve, tests need to be updated, which can add overhead and increase development time. 
