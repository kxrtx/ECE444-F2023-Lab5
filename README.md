# ECE444-F2023-Lab5

Completed the replay.

Included a test case on:

[https://github.com/ECE444-2023Fall/Blue-Surf/pull/46
](https://github.com/ECE444-2023Fall/Blue-Surf/blob/f39e89e418bc0f0155c2f6e3fe8ede969dc4143d/backend/tests/test_app.py#L22-L45)

[https://github.com/ECE444-2023Fall/Blue-Surf/blob/FE-landing-page/backend/tests/test_app.py.](https://github.com/ECE444-2023Fall/Blue-Surf/pull/46)

What are the pros and cons of TDD?

Test-driven development is beneficial when considering the quality of code, confidence in testing, and better documentation and processes. TDD refers to multiple smaller units of testable code, which allows for higher code quality as it is not rushed at the very end of development. Due to these multiple tests, the developers must focus on writing strong necessary code to pass the tests, allower better attention to sections of code. Because the code has many forms of testing for each section, changes to the code can be made with more confidence since it is in sections and any error can be found and evaluated/addressed faster through the identification from unit tests. Another reason the use of TDD is beneficial is due to the documentation and process, as it also fits well with the Agile Method. TDD also serves as a form of documentation since it addresses multiple smaller components of the code, providing insight into the expected behaviour of the code. This form of documentation through tests makes it easier for new developers to decompose elements and further understand how the code is supposed to work.

Some negatives when considering TDD include the time commitment and maintenance. TDD requires writing tests alongside code, which may be slow, as writing tests before the actual code takes additional time and thought. This can be difficult in environments that require fast-paced development or high competition in terms of time. This time investment can take away from resources dedicated to the actual code. Additionally, TDD may lead to difficulty in maintenance as updating so many tests can be hard to do as the code grows. With changes, many tests may be required to be modified, as the tests must be modified to consider the updated code.
