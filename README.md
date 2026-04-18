<style>
  table.icon-table {
    border-collapse: collapse;
    border: none;
  }

  table.icon-table tr,
  table.icon-table td {
    border: none;
  }

  table.icon-table td {
    text-align: center;
    vertical-align: middle;
    padding: 0;
  }

  table.icon-table img {
    display: block;
    margin: 0 auto;
  }
</style>

<hr />

# Jacob Badenhorst • Quality Engineer • APAC / NZ / AU

## About Me

As a Quality Engineer, I lead quality assurance initiatives for technology projects spanning various industries and global technology sectors.

My professional experience and interests are focused on open-source test automation frameworks, with a particular emphasis on containerised solutions deployed and orchestrated within cloud-based CI/CD pipelines. 

I actively explore the integration of AI technologies and Model Context Protocol (MCP) standards to enhance test automation for productivity, scalability, and maintainability.
<br />
#### [View my online resume](https://badj.github.io/online-resume/)
<hr />

## Experience: Test Frameworks/Stacks • Development Stacks • Languages • AI models • MCP

* **Frameworks and Libraries:** Playwright, Cypress, Selenium, Webdriver, JMeter, Spock, Geb, Jest, Selendroid, Appium, Espresso, JUnit, NUnit, Capybara, Spring Boot, UiAutomator, XCUITest, BATS-CORE (Bash Automated Testing System)
* **Languages:** TypeScript, JavaScript, Java, Groovy, Ruby, SQL, Shell/Bash/scripting.
* **API testing, automation, and stubbing:** SOAP UI, Postman, Newman, Wiremock, REST Assured.
* **Build, Continuous Integration and Continuous Delivery (CI/CD):** GitHub Actions/Workflows, Gradle, Maven, Ant, Jenkins, GitLab CI, Bamboo.
* **BDD, SBE, and TDD:** Cucumber, Concordion, RSpec
* **AI models and Model Context Protocol (MCP):** Claude Sonnet, ChatGPT, GitHub Copilot, Playwright MCP, GitHub MCP Server.

<hr />

## Project statuses: Build • Deployment • Test runs

| **Project / Repo**                                                                                                      | **Description • Project statuses: Build • Deployment • Test runs**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |                                                                                                                                                                                                                                                                                                                                                                                    
|:------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [**NZ Goverment Debt Trends 2002-2025**](https://github.com/badj/NZGovDebtTrends2002-2025)                              | An interactive HTML graph built with [Plotly JS](https://plotly.com/graphing-libraries/) to visualise [New Zealand Government Debt Trends from 2002–2025](https://badj.github.io/NZGovDebtTrends2002-2025/) hosted with [GitHub Pages](https://docs.github.com/en/pages) <br/> The project includes [GitHub Action](https://github.com/features/actions) CI/CD [Playwright](https://playwright.dev/) automated end-to-end testing to verify page and graph features. <br/> [Playwright MCP](https://github.com/microsoft/playwright-mcp) was used with [GitHub Copilot](https://github.com/copilot), [Claude Sonnet](https://www.anthropic.com/claude/sonnet) and [Chat-GPT](https://chatgpt.com/) agent prompts to generate and fix automated tests. <br/> <br/> [![pages-build-deployment](https://github.com/badj/NZGovDebtTrends2002-2025/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/badj/NZGovDebtTrends2002-2025/actions/workflows/pages/pages-build-deployment) <br/> [![Playwright Tests](https://github.com/badj/NZGovDebtTrends2002-2025/actions/workflows/main.yml/badge.svg)](https://github.com/badj/NZGovDebtTrends2002-2025/actions/workflows/main.yml) |
| [**Api with Cypress e2e Tests POC**](https://github.com/badj/api-with-cypress-e2e-tests-poc)                            | A POC for a [Node.js](https://nodejs.org/en) CRUD [Express.js API](https://expressjs.com/) with: <br/> [Swagger API Documentation](https://swagger.io/), [JEST](https://jestjs.io/) with [SuperTest](https://github.com/forwardemail/supertest) for Unit tests and [Cypress](https://www.cypress.io/) E2E Tests coverage. <br/> <br/> [![Item API Deploy and E2E Cypress Tests](https://github.com/badj/api-with-cypress-e2e-tests-poc/actions/workflows/main.yml/badge.svg)](https://github.com/badj/api-with-cypress-e2e-tests-poc/actions/workflows/main.yml)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| [**Playwright POC**](https://github.com/badj/playwright-poc)                                                            | This repo contains a POC for [Playwright](https://playwright.dev/) as a test framework for checkout journey tests on the ["Test Automation - Big Cartel E-commerce Test store"](https://testautomation.bigcartel.com/) showcasing: <br/> [Playwright](https://playwright.dev/) Tests and [Apache JMeter](https://jmeter.apache.org/) Load Test Frameworks with [Monocart](https://github.com/cenfun/monocart-reporter) and [Allure](https://allurereport.org/) reporters to run locally or in [Docker](https://www.docker.com/) using [GitHub Action](https://github.com/features/actions) workflows. <br/> <br/> [![Playwright Tests in Docker](https://github.com/badj/playwright-poc/actions/workflows/main.yml/badge.svg)](https://github.com/badj/playwright-poc/actions/workflows/main.yml)<br/> [![JMeter Performance Tests in Docker](https://github.com/badj/playwright-poc/actions/workflows/jmeter-load-test.yml/badge.svg)](https://github.com/badj/playwright-poc/actions/workflows/jmeter-load-test.yml)                                                                                                                                                                                    |
| [**CACHE-CLEANER**](https://github.com/badj/CACHE-CLEANER)                                                              | A simple, safe, and visual [bash script](https://www.w3schools.com/bash/bash_script.php) that completely clears the [Stremio](https://www.stremio.com) cache on macOS, freeing up disk space with a nice progress display and final summary. Perfect for users who notice Stremio taking up several gigabytes of cache over time. <br/> Project / Repo includes test coverage with [BATS-CORE](https://github.com/bats-core/bats-core) and [GitHub Actions](https://github.com/features/actions) for CI/CD. <br/> <br/> [![Test CLEAR-STREMIO-CACHE in Docker](https://github.com/badj/CACHE-CLEANER/actions/workflows/test-clear-cache.yml/badge.svg)](https://github.com/badj/CACHE-CLEANER/actions/workflows/test-clear-cache.yml)                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | 
| [**Cypress Cucumber POC**](https://github.com/badj/cypress-cucumber-poc)                                                | This repo contains a POC for [Cypress](https://www.cypress.io/) as a test framework for checkout journey tests on the ["Test Automation - Big Cartel E-commerce Test store"](https://testautomation.bigcartel.com/) showcasing: <br/> Cypress Test Framework with [Cucumber BDD](https://cucumber.io/) and [Mochawesome reporter](https://www.npmjs.com/package/cypress-mochawesome-reporter) running locally or in [Docker](https://www.docker.com/) using [GitHub Action](https://github.com/features/actions) workflows. <br/> <br/> [![Cypress Tests in Docker](https://github.com/badj/cypress-cucumber-poc/actions/workflows/main.yml/badge.svg)](https://github.com/badj/cypress-cucumber-poc/actions/workflows/main.yml)                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| [**HackerNews Top100 articles Sorting Playwright Test**](https://github.com/badj/HackerNewsTop100SortingPlaywrightTest) | [Playwright](https://playwright.dev/) test script that validates that the first 100 [Hacker News](https://news.ycombinator.com/newest) articles are sorted from newest to oldest with [Monocart](https://github.com/cenfun/monocart-reporter) test reporter support. The project was created for a [QA Wolf](https://www.qawolf.com/) take home [assignment](https://www.task-wolf.com/apply-qae). <br/> <br/> [![Playwright Tests in Docker](https://github.com/badj/HackerNewsTop100SortingPlaywrightTest/actions/workflows/main.yml/badge.svg)](https://github.com/badj/HackerNewsTop100SortingPlaywrightTest/actions/workflows/main.yml)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| [**Online Resume**](https://github.com/badj/online-resume)                                                              | Personal Online resume hosted with [GitHub Pages](https://docs.github.com/en/pages). <br/> <br/> [![pages-build-deployment](https://github.com/badj/online-resume/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/badj/Online-Resume/actions/workflows/pages/pages-build-deployment)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |

<hr />

## Repo projects • Development and Test Stacks/Frameworks implemented

<br/>
<table class="icon-table">
  <tr>
    <td><img alt="rubymine-original" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/rubymine/rubymine-original.svg"></td>
    <td><img alt="intellij" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/intellij/intellij-original.svg"></td>
    <td><img alt="Rafa-webstorm" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/webstorm/webstorm-original.svg"></td>
    <td><img alt="Rafa-express-original-wordmark" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/express/express-original-wordmark.svg"></td>
    <td><img alt="Rafa-markdown" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/markdown/markdown-original.svg"></td>
    <td><img alt="Rafa-swagger" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/swagger/swagger-original.svg"></td>
    <td><img alt="Rafa-plotly" height="60" width="70" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/plotly/plotly-original-wordmark.svg"></td>
</tr>
  <tr>
    <td><img alt="Rafa-HTML" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg"></td>
    <td><img alt="Rafa-npm" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/npm/npm-original-wordmark.svg"></td>
    <td><img alt="Rafa-nodejs" height="60" width="70" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/nodejs/nodejs-line-wordmark.svg"></td>
    <td><img alt="Rafa-react" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/react/react-original-wordmark.svg"></td>
    <td><img alt="jquery-plain-wordmark" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/jquery/jquery-plain-wordmark.svg"></td>
    <td><img alt="Rafa-CSS" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg"></td>
    <td><img alt="Rafa-yaml" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/yaml/yaml-original.svg"></td>
</tr>    
  <tr>
    <td><img alt="Rafa-json-original" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/json/json-original.svg"></td>
    <td><img alt="Ruby_logo" height="50" width="50" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/ruby/ruby-plain-wordmark.svg"></td>
    <td><img alt="Java_logo" height="50" width="50" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/java/java-original-wordmark.svg"></td>
    <td><img alt="Groovy-logo" height="70" width="70" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/groovy/groovy-original.svg"></td>
    <td><img alt="Bash-logo" height="50" width="50" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/bash/bash-original.svg"></td>
    <td><img alt="Rafa-javascript" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/javascript/javascript-original.svg"></td>
    <td><img alt="Rafa-maven-original-wordmark" height="80" width="80" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/maven/maven-original-wordmark.svg"></td>
</tr>
  <tr>
    <td><img alt="Rafa-typescript" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/typescript/typescript-plain.svg"></td>
    <td><img alt="rails-original-wordmark" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/rails/rails-original-wordmark.svg"></td>
    <td><img alt="spring-original-wordmark" height="60" width="55" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/spring/spring-original-wordmark.svg"></td>
    <td><img alt="rspec-plain-wordmark" height="80" width="80" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/rspec/rspec-plain-wordmark.svg"></td>
    <td><img alt="Rafa-jest" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/jest/jest-plain.svg"></td>
    <td><img alt="Rafa-junit" height="80" width="90" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/junit/junit-original-wordmark.svg"></td>
    <td><img alt="Rafa-mocha-original" height="50" width="50" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/mocha/mocha-original.svg"></td>
</tr>
  <tr>
    <td><img alt="Rafa-cypressio" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/cypressio/cypressio-original.svg"></td>
    <td><img alt="Rafa-playwright" height="60" width="70" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/playwright/playwright-original.svg"></td>
    <td><img alt="Bats-core-logo" height="50" width="50" src="https://raw.githubusercontent.com/bats-core/bats-core/master/docs/source/assets/light_mode_cube.svg"></td>
    <td><img alt="Apache_JMeter-logo" height="50" width="100" src="https://upload.wikimedia.org/wikipedia/en/e/e6/Apache_JMeter_Logo.svg"></td>
    <td><img alt="Appium-logo" height="50" width="60" src="https://browserstack.wpenginepowered.com/wp-content/uploads/2024/07/Appium.svg"></td>
    <td><img alt="Xcuitest-logo" height="50" width="60" src="https://browserstack.wpenginepowered.com/wp-content/uploads/2024/07/Xcuitest.svg"></td>
    <td><img alt="WebdriverIO-logo" height="50" width="60" src="https://browserstack.wpenginepowered.com/wp-content/uploads/2024/07/WebdriverIO.svg"></td>
</tr>
  <tr>
    <td><img alt="Rafa-cucumber" height="90" width="110" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/cucumber/cucumber-plain-wordmark.svg"></td>
    <td><img alt="Rafa-postman-original" height="50" width="50" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/postman/postman-original.svg"></td>
    <td><img alt="Rafa-github-original-wordmark" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/github/github-original-wordmark.svg"></td>
    <td><img alt="Rafa-githubactions" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/githubactions/githubactions-plain-wordmark.svg"></td>
    <td><img alt="Rafa-linux-original" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/linux/linux-original.svg"></td>
    <td><img alt="Rafa-ubuntu" height="80" width="90" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/ubuntu/ubuntu-original-wordmark.svg"></td>
    <td><img alt="Rafa-docker" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/docker/docker-original-wordmark.svg"></td>
</tr>
  <tr>
    <td><img alt="Rafa-chrome-plain-wordmark" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/chrome/chrome-plain-wordmark.svg"></td>
    <td><img alt="Rafa-firefox-plain-wordmark" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/firefox/firefox-plain-wordmark.svg"></td>
    <td><img alt="Rafa-safari-plain-wordmark" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/safari/safari-plain-wordmark.svg"></td>
    <td><img alt="Rafa-electron-original" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/electron/electron-original.svg"></td>
    <td><img alt="claude-logo" height="50" width="60" src="https://browserstack.wpenginepowered.com/wp-content/uploads/2025/08/claude_desktop.svg"></td>
    <td><img alt="github_copilot-logo" height="50" width="60" src="https://browserstack.wpenginepowered.com/wp-content/uploads/2025/08/github_copilot.svg"></td>
    <td><img alt="Model_Context_Protocol_logo" height="50" width="60" src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fe/Model_Context_Protocol_logo.svg/500px-Model_Context_Protocol_logo.svg.png"></td>
</tr>
</table>
<br/>
<hr />
