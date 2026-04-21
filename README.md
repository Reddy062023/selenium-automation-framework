@"

\# Selenium Automation Framework



A production-grade, unified test automation framework built with Java, Selenium WebDriver, TestNG, and Cucumber BDD.



\## Tech Stack



| Layer | Technology |

|---|---|

| Language | Java |

| Browser Automation | Selenium WebDriver |

| Test Framework | TestNG |

| BDD | Cucumber |

| Build Tool | Maven |

| Reporting | Extent Reports |

| Design Pattern | Page Object Model (POM) |



\## Project Structure



\- AbstractComponents — Base component with reusable Selenium actions

\- pageobjects — LandingPage, CartPage, CheckoutPage, ConfirmationPage, OrderPage, ProductCatalogue, InventoryPage

\- utils — DriverFactory, ExtentListener, ExtentManager

\- tests — 9 test classes covering E2E, API, UI components

\- cucumber — BDD feature files and step definitions

\- testSuites — TestNG XML suites for targeted runs



\## Test Coverage



| Test | Type |

|---|---|

| SubmitOrderTest | E2E order flow |

| ErrorValidationsTest | Negative testing |

| APIInvalidStatusTest | API validation |

| CalendarTest | Date picker |

| DragDropTest | Drag and drop |

| MultipleWindowTest | Multi-window handling |

| WaitTest | Wait strategies |

| WebTableTest | Web table parsing |



\## Run Tests



mvn test -DsuiteXmlFile=testSuites/testng.xml



\## Author



Japendra | QA Automation Engineer | Selenium, Java, TestNG, Cucumber

GitHub: https://github.com/Reddy062023

"@ | Out-File -FilePath "C:\\selenium-automation-framework\\README.md" -Encoding utf8

