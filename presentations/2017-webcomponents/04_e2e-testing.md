# E2E testing

> End-to-end testing is a methodology used to test whether the flow of an application is performing as designed from start to finish. The purpose of carrying out end-to-end tests is to identify system dependencies and to ensure that the right information is passed between various system components and systems.

---
# Confusion

Acceptance Testing is often confused with End-to-End Testing

Acceptance Testing (or User Acceptance Testing) is a **phase** in the testing process

E2E-Testing is a **means** to verify application behavior during Acceptance Test phase

Note:
When talking about testing Acceptance tests and E2E tests are often confused and spoken about as the same thing. This is not the case. 
Acceptance testing is a phase in the testing process, also called User Acceptance Testing. 

--- 
# Proportions
![testing pyramid](img/test_pyramid.png)

On top of the pyramid there are fewer tests, but the tests are larger and slower. 

--- 
# Tooling

Selenium dominates open-source market for E2E-testing

Alternatives _are_ available, but often less advanced

Wrapper such as _webdriver.io_ are high-level libraries that use Selenium