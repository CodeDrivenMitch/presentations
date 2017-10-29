# E2E testing

> End-to-end testing is a methodology used to test whether the flow of an application is performing as designed from start to finish. The purpose of carrying out end-to-end tests is to identify system dependencies and to ensure that the right information is passed between various system components and systems.

---
# Confusion

Acceptance tests are often confused with E2E-tests. 

--- 
# Proportions
![testing pyramid](img/test_pyramid.png)

On top of the pyramid there are fewer tests, but the tests are larger and slower. 

--- 
# Tooling

Selenium dominates open-source market for E2E-testing

Alternatives _are_ available, but often less advanced

Wrapper such as _webdriver.io_ are high-level libraries that use Selenium