## **Title**
[Lean Testing or Why Unit Tests are Worse than You Think](https://blog.usejournal.com/lean-testing-or-why-unit-tests-are-worse-than-you-think-b6500139a009)

## **About**
An article that I find interesting is Eugen Kiss's *Lean Testing or Why Unit Tests are Worse than You Think*. Kiss examines unit testing from an economical perspective. He claims that end-to-end and integration tests are economically better than unit tests because they cover a larger portion of the codebase. This allows it to provide more confidence than unit tests. Unit tests may test edge cases that are not typically used, while end-to-end tests for critical/most common paths a user might take. Furthermore, Kiss claims that unit tests are an 'anti-architectural' device due to its `high maintenance liabilities`. For example, refactoring code may make the unit tests non-functional, which requires rewriting them, which is time-consuming. Therefore, unit tests may not give a good return on investment.


From what we learned in class, it seems that unit tests are less desirable in the agile methodology. Since refactoring old code with new code is a common procedure in the agile method, then the unit tests would also need to be refactored, which would be time-consuming.  

## **Additional Comments**

I appreciated the way the author went through an economical approach when
it came to unit testing the code. I felt that this brought a rather unique but
heavily important view to unit testing which changed the way I will approach this
topic in the future.

--Kevin Maldjian

## **Additional Comments**



--Anandini Chawla 

The author gives a solid insight into pros and cons of units testing and end-to-end integration tests. Unit testing
is a more common approach it is interesting to note that end-to-end integration tests may be more economical and
useful. Additionally, end-to-end integration tests will also save time, as they negate unnecesary testing to edge
cases, which require considerable degugging and refactoring. 


