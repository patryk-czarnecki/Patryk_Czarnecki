# Portfolio
## About Me
I am a graduate in Occupational Health and Safety. During my student internships, I learned the importance of time management and team communication. I acquired skills in document management, problem-solving, data analysis, and drawing conclusions from available information.

I have a solid foundation in manual testing, gained through online courses, webinars, blogs, YouTube channels, and Facebook groups. As part of my self-improvement, I tested popular websites and created test cases, which I managed using TestLink and Xray, and reported progress in Jira. I also created REST API tests in Postman and end-to-end (E2E) tests using JavaScript and Cypress. Additionally, I gained knowledge about tools such as Docker and Jenkins.

I am a meticulous, analytical, and determined person, constantly striving to improve my skills. Learning the art of software testing brings me great joy.

## Projects

### [Project 1: Manual Testing](https://github.com/patryk-czarnecki/Project1-Manual-Testing)

This project involved conducting **manual functional testing** of the e-commerce website [https://skleptest.pl/](https://skleptest.pl/). The main goal was to verify key user functionalities such as **registration**, **login**, **product browsing**, and **shopping cart management**. The tests were conducted in a test environment using the **Ubuntu** operating system and the **Google Chrome** browser.

The testing focused on verifying whether users could successfully:
- Create accounts
- Log in
- Browse products
- Use filters and search functionality
- Manage the shopping cart (adding items, updating quantities, and removing products)

Test cases were created and managed using **TestLink**, while **Jira** was used for reporting and tracking defects. A total of **18 test cases** were executed, with:
- **10 passing**
- **6 failing**
- **2 blocked due to bugs**

Critical and major issues were identified, specifically in:
- User registration
- Product browsing
- Shopping cart functionalities

Based on the test results, it was recommended to fix the critical issues and conduct a retest to ensure the issues were resolved successfully.

### [Project 2: Automated Testing - Cypress](https://github.com/patryk-czarnecki/Project-2-Automated-Testing---Cypress)

This project involved **automated functional testing** of the e-commerce website [https://skleptest.pl/](https://skleptest.pl/). The focus was on testing key user functionalities such as **registration**, **login**, and **shopping cart features**. The tests were carried out using **Cypress**, a browser automation tool, in an environment that included the **Ubuntu** operating system and **Google Chrome** browser.

The scope of the tests included:

- Verifying that new users could register successfully.
- Logging in with valid and invalid credentials.
- Ensuring that shopping cart functionalities like adding products, updating quantities, and removing items worked correctly.

Test cases were automated for each of these features and executed using Cypress. Example test cases included:

- **Registration**: Verifying successful registration with valid data and displaying an error when using an already registered email.
- **Login**: Ensuring successful login with correct credentials, and handling errors for incorrect password, non-existent email, and empty fields.
- **Shopping Cart**: Testing the ability to add a product to the cart, update product quantity, and remove products.

Additionally, the project utilized the **Page Object Model (POM)** design pattern to improve the maintainability and scalability of the test code. Each page of the application was organized into separate classes to better manage test logic.

The tests were also integrated with **Jira** for defect tracking and **GitHub Actions** to enable automatic test execution in a CI/CD pipeline.

The final recommendation was to continue expanding the test automation coverage and ensure close collaboration between the testing and development teams to address identified issues.

### [Project 3: API Testing](https://github.com/patryk-czarnecki/Project3-APITesting)
This project involved testing the **JSONPlaceholder API** to validate its key functionalities, including handling various HTTP requests such as **GET**, **POST**, **PUT**, and **DELETE**. The main objective was to ensure that the API performed as expected across different endpoints and methods. The tests were focused on functional and performance aspects, covering important endpoints like retrieving posts, creating new posts, updating existing posts, and deleting posts.

The testing environment included tools such as **Postman**, **Newman**, **JMeter**, and **Jenkins** for automation and performance testing. Functional tests verified the correct behavior of API requests, while performance tests checked the API's response time and scalability.

Test cases were designed and managed in Postman, while reports were generated using Newman and JMeter. Key test scenarios included:

- **GET /posts**: Checking if the API successfully returns a list of posts.
- **POST /posts**: Ensuring that new posts are created with correct data.
- **PUT /posts/:id**: Verifying that existing posts can be updated.
- **DELETE /posts/:id**: Confirming that posts can be deleted by ID.

The tests were automated and integrated into a **Jenkins** pipeline, enabling continuous testing and reporting. The pipeline was set up to fetch the latest code, run the tests, and generate detailed reports for review.

The results indicated that most of the API endpoints worked as expected, with some minor issues in performance. The test results were shared in the form of HTML reports, highlighting response times and any functional failures. Based on the findings, recommendations were made to optimize API response times and resolve any discrepancies before further deployment.

## Courses
* [SQL Course from Scratch | MySQL](https://www.udemy.com/course/kurs-sql-od-podstaw)
* [Software Testing in Practice | Bootcamp](https://www.udemy.com/course/testowanie-oprogramowania-w-praktyce-bootcamp)
* [Practical Software Testing Course](https://www.udemy.com/course/praktyczny-kurs-testowania-oprogramowania)
* [Jira Course from Scratch - Project Management](https://www.udemy.com/course/kurs-jira-od-podstaw-zarzadzanie-projektami)
* [ChatGPT in Software Testing](https://www.udemy.com/course/chatgpt-w-testowaniu-oprogramowania)
* [Postman from Scratch - REST API Testing](https://www.udemy.com/course/postman-od-podstaw-testowanie-rest-api)
* [Interview Questions and Answers for Testers](https://www.udemy.com/course/pytania-i-odpowiedzi-rekrutacyjne-dla-testera)
* [Cypress from Scratch - Test Automation](https://www.udemy.com/course/cypress-od-podstaw)
* [Chrome DevTools: From Basics to Expert](https://www.udemy.com/course/chrome-devtools-od-podstaw-do-eksperta)
* [Docker: Practical Course from Scratch](https://www.udemy.com/course/docker-praktyczny-kurs-od-podstaw)

## Technical Skills

### Programming and Scripting Languages
* JavaScript
* SQL (MySQL)
* HTML, CSS, JSON, XPath

### Testing Tools
* Cypress
* Postman
* Newman
* JMeter
* TestLink
* Xray
* DevTools

### Version Control and CI/CD
* Git
* GitHub
* GitHub Actions
* Jenkins

### Reporting and Documentation
* Jira
* Bug Reporting
* Test Case Creation
* Trello
* Markdown

### Development Tools
* Visual Studio Code
* Docker
* MySQL Workbench
* Xampp

### Miscellaneous Tools
* PicPick
* ShareX

## Gallup Test
1. Compliance
2. Analyst
3. Gathering
4. Impartiality
5. Discipline

## Books
* [Testowanie Oprogramowania - Piotr Wicherski](https://ksiazka.testowanieoprogramowania.pl/od-czego-zaczac)
* [Zawód tester - Radosław Smilgin](https://lubimyczytac.pl/ksiazka/291227/zawod-tester)
* [Certyfikowany tester ISTQB. Poziom podstawowy - Adam Roman, Lucjan Stapp](https://lubimyczytac.pl/ksiazka/4943677/certyfikowany-tester-istqb-poziom-podstawowy)

## IT groups I follow on Facebook
* [Testowanie oprogramowania](https://www.facebook.com/groups/TestowanieOprogramowania)
* [Testowanie oprogramowania - Materiały | Porady](https://www.facebook.com/groups/testowanie)

## Blogs
* [AkademiaQA](https://akademiaqa.pl/)
* [Po szklanie i na testowanie](https://poszklanieinatestowanie.pl/)
* [RemigiuszBednarczyk.pl](https://remigiuszbednarczyk.pl/)
* [Rafał Podraza](https://www.youtube.com/channel/UC0d8tgd-z-4fVvKnDLwCxzA)
* [Testowanie oprogramowania](https://testowanie-oprogramowania.pl/)
* [Quality Island](https://qualityisland.pl/blog/)
* [Wyszkolewas.com.pl](https://www.wyszkolewas.com.pl/)

## Webinars
* Accessibility Testing and WCAG 2.2 Standard
* REST API Testing for Beginners
* AI in Software Testing: The Future of Testing
* Performance Testing - An Increasingly Essential Skill for Software Testers
* Mobile App Testing: Techniques, Challenges, and Best Practices

