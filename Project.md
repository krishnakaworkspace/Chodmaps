#  30-Day Practical Developer Project Roadmap

> **Goal:** Har din ek real project feature build karo. Sirf tutorials/watch nahi — **Day 1 se code**, aur Day 30 tak ek working, demonstrable project.

This roadmap is based on the Developer Roadmaps Handbook. The original handbook organizes each track around foundations → core skills → depth/tooling → integration/shipping. Here, those topics are converted into **practical daily project tasks**.

---

## How to use this README

1. **Sirf ek track choose karo.**
2. Har day ka task project mein actually implement karo.
3. Task complete hone par `[ ]` ko `[x]` karo.
4. Har din meaningful Git commit karo.
5. Week ke end par working version save/demo karo.
6. Day 30 par project ko polish, document and ship karo.

### Daily rule

**Learn → Build → Test → Commit**

Target: roughly **2–3 hours/day**. Agar time kam hai, task ko next day continue karo; double workload karke catch-up mat karo.

---

# 1. Frontend Development

### Capstone: Personal Productivity Dashboard

Build a responsive web app where a user can manage tasks, view progress, and use a simple dashboard.

| Day | Practical project task | Done |
|---|---|---|
| 1 | Create the project repo and build the basic HTML page structure: header, sidebar, main content and footer. | [ ] |
| 2 | Add a dashboard layout with sections for **Tasks, Progress, Quick Actions and Profile**. | [ ] |
| 3 | Add task cards with title, description, priority and status using semantic HTML. | [ ] |
| 4 | Add a task creation form with text inputs, select fields, checkbox and submit button. | [ ] |
| 5 | Make the HTML semantic and add basic SEO metadata, page title and accessible labels. | [ ] |
| 6 | Create the first complete static version of the dashboard in pure HTML. | [ ] |
| 7 | Polish Week 1: clean structure, add sample data, test links/forms and commit the working version. | [ ] |
| 8 | Add the main CSS system: typography, spacing, buttons, cards and page background. | [ ] |
| 9 | Style the sidebar, navigation and dashboard header. | [ ] |
| 10 | Rebuild the dashboard layout using **Flexbox** where appropriate. | [ ] |
| 11 | Use **CSS Grid** for the dashboard cards and statistics layout. | [ ] |
| 12 | Make the complete dashboard responsive for mobile, tablet and desktop. | [ ] |
| 13 | Add visual states: hover, active, completed, priority and disabled states. | [ ] |
| 14 | Finish the responsive UI and test it at multiple screen sizes. | [ ] |
| 15 | Add JavaScript state for creating a new task from the form. | [ ] |
| 16 | Add task delete and complete/uncomplete functionality. | [ ] |
| 17 | Add filtering: All, Active, Completed and High Priority. | [ ] |
| 18 | Connect the DOM to a task array and render task cards dynamically. | [ ] |
| 19 | Add localStorage so tasks remain after refreshing the browser. | [ ] |
| 20 | Initialize Git properly, create meaningful commits and push the project to GitHub. | [ ] |
| 21 | Add npm and a simple build/dev workflow to the project. | [ ] |
| 22 | Convert the dashboard into a React project and create reusable components. | [ ] |
| 23 | Create React components for Sidebar, Header, TaskCard, TaskForm and Stats. | [ ] |
| 24 | Move task data into React state and rebuild add/delete/complete actions. | [ ] |
| 25 | Add effects/local persistence and keep the UI synchronized with stored tasks. | [ ] |
| 26 | Add routing with a second page: **Dashboard → Tasks**. | [ ] |
| 27 | Restyle the React app with Tailwind or another CSS framework from the handbook resources. | [ ] |
| 28 | Add a simple PWA-style experience and improve loading/error/empty states. | [ ] |
| 29 | Audit accessibility, keyboard navigation, responsive behavior and privacy-related basics. | [ ] |
| 30 | Final polish, deploy the project, add screenshots and write a complete README explaining setup and features. | [ ] |

**Final deliverable:** Live responsive React productivity dashboard.

---

# 2. Backend Development

### Capstone: Task Manager REST API

Build a backend that supports users, tasks, database storage, authentication-ready structure, testing and Docker.

| Day | Practical project task | Done |
|---|---|---|
| 1 | Create the backend repo and define the Task Manager API: tasks, users, statuses and priorities. | [ ] |
| 2 | Create a tiny frontend/test page that will consume your API later. | [ ] |
| 3 | Create a basic HTTP server and implement a health endpoint: `GET /health`. | [ ] |
| 4 | Add request routing and return JSON responses for API endpoints. | [ ] |
| 5 | Create the project structure and environment configuration. | [ ] |
| 6 | Build Linux/terminal scripts for installing, running and stopping the project. | [ ] |
| 7 | Week 1 checkpoint: API starts cleanly, health endpoint works and project is committed to Git. | [ ] |
| 8 | Create the Node.js application and add the required modules. | [ ] |
| 9 | Add configuration for development/production environments. | [ ] |
| 10 | Build the initial task CRUD API in memory. | [ ] |
| 11 | Set up Git branches/commits and create a clean GitHub repository. | [ ] |
| 12 | Create the PostgreSQL database and design the users/tasks tables. | [ ] |
| 13 | Write SQL for create, read, update, delete and filtering tasks. | [ ] |
| 14 | Connect Node.js to PostgreSQL and replace the in-memory task storage. | [ ] |
| 15 | Create a MongoDB version of one resource to understand the NoSQL model. | [ ] |
| 16 | Decide the primary database for the project and document why. | [ ] |
| 17 | Move the API to Express and create proper REST routes. | [ ] |
| 18 | Add controllers for task creation, listing, update and deletion. | [ ] |
| 19 | Add validation and consistent API error responses. | [ ] |
| 20 | Refactor into **routes → controllers → models/services** (MVC-style structure). | [ ] |
| 21 | Add caching for a read-heavy endpoint and document where caching helps. | [ ] |
| 22 | Add Helmet/security headers, environment secrets and basic request validation. | [ ] |
| 23 | Write unit tests for task/business logic. | [ ] |
| 24 | Write API/integration tests for the main endpoints. | [ ] |
| 25 | Create a Dockerfile for the backend. | [ ] |
| 26 | Create Docker Compose configuration for the API and database. | [ ] |
| 27 | Run the complete stack in containers and fix environment/configuration issues. | [ ] |
| 28 | Prepare production deployment and add a production-style web server/reverse-proxy setup where appropriate. | [ ] |
| 29 | Final capstone sprint: test all endpoints, clean logs, improve error handling and documentation. | [ ] |
| 30 | Deploy the API, publish API documentation/examples and add setup instructions to the README. | [ ] |

**Final deliverable:** Deployed REST API with database, tests and Docker.

---

# 3. Android Development

### Capstone: Expense Tracker Android App

Build a native Android app where users can record expenses, browse them and calculate totals.

| Day | Practical project task | Done |
|---|---|---|
| 1 | Create the Android Studio project, run it on an emulator and replace the starter screen with your app home screen. | [ ] |
| 2 | Create the Kotlin data model for an expense. | [ ] |
| 3 | Add Kotlin functions to calculate totals and format expense data. | [ ] |
| 4 | Add validation/null-safety handling to the expense model and form logic. | [ ] |
| 5 | Build the main expense-entry layout. | [ ] |
| 6 | Build the expense list layout and reusable item UI. | [ ] |
| 7 | Week 1 build: make a single-screen working expense calculator. | [ ] |
| 8 | Add button/input events to create a new expense. | [ ] |
| 9 | Add scrolling and display expense items in a list. | [ ] |
| 10 | Improve list item UI with amount, category, date and note. | [ ] |
| 11 | Implement RecyclerView for the expense list. | [ ] |
| 12 | Add a second activity/screen for creating an expense. | [ ] |
| 13 | Pass the created expense data back to the main screen. | [ ] |
| 14 | Add an implicit intent to share an expense summary. | [ ] |
| 15 | Add a networking layer for fetching sample categories or currency data. | [ ] |
| 16 | Create the API data model and networking interface. | [ ] |
| 17 | Use Retrofit to fetch JSON from a public API. | [ ] |
| 18 | Display fetched API data inside the app. | [ ] |
| 19 | Refactor one part of the app using fragments. | [ ] |
| 20 | Add a second fragment for expense statistics. | [ ] |
| 21 | Refactor the app to separate UI, data and business logic. | [ ] |
| 22 | Introduce a clean application architecture structure. | [ ] |
| 23 | Move API/database logic out of Activities/Fragments. | [ ] |
| 24 | Add monthly expense totals and category summaries. | [ ] |
| 25 | Add filtering by category and date. | [ ] |
| 26 | Add edit and delete expense functionality. | [ ] |
| 27 | Improve loading, empty and error states. | [ ] |
| 28 | Test the app on multiple emulator/device sizes and fix UI issues. | [ ] |
| 29 | Add app icon, screenshots and final UI polish. | [ ] |
| 30 | Build a release version, document the project and create a final demo/screenshots. | [ ] |

**Final deliverable:** Working native Android expense tracker.

---

# 4. iOS Development

### Capstone: Habit Tracker iOS App

Build a SwiftUI habit tracker with navigation, API integration, persistence and MVVM structure.

| Day | Practical project task | Done |
|---|---|---|
| 1 | Create the Xcode project and build the first SwiftUI home screen. | [ ] |
| 2 | Create a `Habit` model using Swift structs and basic properties. | [ ] |
| 3 | Add Swift functions for streaks, completion percentage and progress. | [ ] |
| 4 | Add optionals, validation and safe handling for habit data. | [ ] |
| 5 | Create reusable SwiftUI components for habit rows/cards. | [ ] |
| 6 | Build the habit list screen. | [ ] |
| 7 | Week 1 build: create a working single-screen habit tracker. | [ ] |
| 8 | Add a form to create a new habit. | [ ] |
| 9 | Add completion/uncompletion interaction. | [ ] |
| 10 | Add progress and streak information to each habit. | [ ] |
| 11 | Build the complete Week 2 habit tracker screen. | [ ] |
| 12 | Add SwiftUI navigation from Home → Habit Detail → Add Habit. | [ ] |
| 13 | Pass selected habit data between screens. | [ ] |
| 14 | Create an API client for a small public REST API. | [ ] |
| 15 | Decode JSON into Swift models with `JSONDecoder`. | [ ] |
| 16 | Display remote data in a SwiftUI screen. | [ ] |
| 17 | Add a POST request or simulated save operation for the API integration. | [ ] |
| 18 | Add local persistence for habits. | [ ] |
| 19 | Make habits load automatically when the app opens. | [ ] |
| 20 | Add a Swift Package using Swift Package Manager and use it where appropriate. | [ ] |
| 21 | Convert one network/persistence operation to `async/await`. | [ ] |
| 22 | Add async loading and error states to the UI. | [ ] |
| 23 | Improve concurrency/error handling and remove unnecessary blocking work. | [ ] |
| 24 | Introduce MVVM with View, ViewModel and Model layers. | [ ] |
| 25 | Move habit business logic into the ViewModel. | [ ] |
| 26 | Refactor the API/persistence layer so views do not handle data operations directly. | [ ] |
| 27 | Add reusable UI components, app icon and final Xcode cleanup. | [ ] |
| 28 | Test the app on different iPhone sizes and fix layout issues. | [ ] |
| 29 | Final polish: animations, empty states, error states and accessibility. | [ ] |
| 30 | Create the release build, screenshots and README with architecture explanation. | [ ] |

**Final deliverable:** SwiftUI habit tracker using MVVM and persistent data.

---

# 5. Flutter Development

### Capstone: Cross-Platform Expense Tracker

Build one Flutter app that runs on Android/iOS with multiple screens, state management and navigation.

| Day | Practical project task | Done |
|---|---|---|
| 1 | Create the Flutter project and run the starter app on an emulator/device. | [ ] |
| 2 | Create Dart models for expenses. | [ ] |
| 3 | Add Dart functions for totals, categories and filtering. | [ ] |
| 4 | Add validation and control-flow logic to the expense form. | [ ] |
| 5 | Create classes/constructors for the core app models. | [ ] |
| 6 | Add reusable model/helper classes and test them with sample data. | [ ] |
| 7 | Week 1 build: create a working Dart expense calculator. | [ ] |
| 8 | Add async functions and mock loading of expense data. | [ ] |
| 9 | Build the Flutter home screen using widgets. | [ ] |
| 10 | Create the expense list screen. | [ ] |
| 11 | Create reusable expense-card widgets. | [ ] |
| 12 | Build the add-expense form. | [ ] |
| 13 | Connect the form to the expense list. | [ ] |
| 14 | Week 2 build: make add/list/delete expense functionality work end-to-end. | [ ] |
| 15 | Introduce your chosen state-management approach (Riverpod or Bloc). | [ ] |
| 16 | Move expense state out of individual UI widgets. | [ ] |
| 17 | Add loading, success and error states to the app. | [ ] |
| 18 | Add category filtering and total calculations through the state layer. | [ ] |
| 19 | Add Material design components and consistent theme configuration. | [ ] |
| 20 | Add Cupertino-style components where useful and make the UI platform-friendly. | [ ] |
| 21 | Add navigation with `go_router`: Home, Add Expense, Details and Statistics. | [ ] |
| 22 | Add Flutter/Dart DevTools debugging and fix at least three issues you discover. | [ ] |
| 23 | Improve performance and remove unnecessary rebuilds. | [ ] |
| 24 | Add local assets/images and configure the asset pipeline. | [ ] |
| 25 | Add stable widget keys where list/form behavior benefits from them. | [ ] |
| 26 | Add persistent local data so expenses survive app restarts. | [ ] |
| 27 | Test Android and iOS layouts and fix platform-specific UI problems. | [ ] |
| 28 | Add empty/loading/error states and final UX polish. | [ ] |
| 29 | Build release versions and verify the main user flow from start to finish. | [ ] |
| 30 | Document architecture, screenshots, setup steps and final features in the README. | [ ] |

**Final deliverable:** One cross-platform Flutter expense tracker.

---

# 6. DevOps

### Capstone: Containerized Full-Stack Deployment

Use a small application as the workload and turn it into a reproducible, monitored deployment pipeline.

| Day | Practical project task | Done |
|---|---|---|
| 1 | Choose a small web/API project as the workload and create its Git repository. | [ ] |
| 2 | Create a Linux-based development environment and run the application from the terminal. | [ ] |
| 3 | Write shell commands/scripts for install, run and cleanup. | [ ] |
| 4 | Add a health-check endpoint and document the application runtime requirements. | [ ] |
| 5 | Create a basic Go utility/service that reports application or system information. | [ ] |
| 6 | Turn the Go utility into a small CLI tool and commit it. | [ ] |
| 7 | Week 1 checkpoint: application + scripts + Go utility run reproducibly. | [ ] |
| 8 | Write a Dockerfile for the application. | [ ] |
| 9 | Build the Docker image and run the app in a container. | [ ] |
| 10 | Add environment variables and configurable application settings. | [ ] |
| 11 | Add Docker Compose for the application and its supporting service/database if needed. | [ ] |
| 12 | Add persistent storage/volumes where appropriate. | [ ] |
| 13 | Add container health checks and restart behavior. | [ ] |
| 14 | Week 2 build: run the complete application stack with one Docker Compose command. | [ ] |
| 15 | Create Kubernetes manifests for the application Deployment. | [ ] |
| 16 | Add a Kubernetes Service and expose the application internally. | [ ] |
| 17 | Add ConfigMap/Secret-based configuration. | [ ] |
| 18 | Run the Kubernetes version locally and debug pod/service issues. | [ ] |
| 19 | Add resource requests/limits and basic deployment configuration. | [ ] |
| 20 | Create a Terraform configuration for a small infrastructure component/environment. | [ ] |
| 21 | Make Terraform configuration repeatable and document its variables/state expectations. | [ ] |
| 22 | Create a CI workflow that installs dependencies and runs tests/builds. | [ ] |
| 23 | Extend CI to build the Docker image. | [ ] |
| 24 | Add automated checks for the container/application. | [ ] |
| 25 | Create a deployment stage for a safe test/staging environment. | [ ] |
| 26 | Add application/container logs and basic monitoring/health metrics. | [ ] |
| 27 | Add alerts or documented checks for failed health status. | [ ] |
| 28 | Perform a failure drill: intentionally break one component and recover it. | [ ] |
| 29 | Clean the repository, improve scripts/docs and verify a fresh-machine setup path. | [ ] |
| 30 | Ship the final DevOps project: repo + Docker + Kubernetes + Terraform + CI/CD + monitoring documentation. | [ ] |

**Final deliverable:** Reproducible containerized application with CI/CD and deployment infrastructure.

> **Safety:** For infrastructure work, use your own/local or authorized environments only.

---

# 7. Blockchain Development

### Capstone: Testnet Crowdfunding DApp

Build a simple crowdfunding smart contract with a web frontend. Use **test networks only** while learning.

| Day | Practical project task | Done |
|---|---|---|
| 1 | Create the project repo and define the crowdfunding flow: create campaign, contribute, view progress. | [ ] |
| 2 | Create a simple web page showing campaign information and contribution UI placeholders. | [ ] |
| 3 | Add wallet-connect UI placeholder and project configuration without handling real funds. | [ ] |
| 4 | Create the Solidity contract structure and define campaign data. | [ ] |
| 5 | Implement campaign creation in the smart contract. | [ ] |
| 6 | Implement contribution tracking using testnet-only logic. | [ ] |
| 7 | Week 1 build: compile the contract and verify the basic contract flow locally. | [ ] |
| 8 | Set up Hardhat or Foundry and organize contracts/tests. | [ ] |
| 9 | Write unit tests for campaign creation. | [ ] |
| 10 | Write tests for contribution accounting and invalid inputs. | [ ] |
| 11 | Add campaign goal/progress calculations. | [ ] |
| 12 | Add controlled withdrawal logic with appropriate access checks. | [ ] |
| 13 | Add events for campaign creation and contributions. | [ ] |
| 14 | Week 2 build: complete the tested local smart-contract version. | [ ] |
| 15 | Add OpenZeppelin components where appropriate instead of rewriting standard security primitives. | [ ] |
| 16 | Add frontend blockchain configuration. | [ ] |
| 17 | Connect the frontend to the contract and read campaign data. | [ ] |
| 18 | Add wallet connection to the testnet application. | [ ] |
| 19 | Add a contribution transaction UI for the test network. | [ ] |
| 20 | Display transaction status: pending, success and failure. | [ ] |
| 21 | Add campaign creation UI and connect it to the contract. | [ ] |
| 22 | Add campaign detail pages and contribution history from contract events. | [ ] |
| 23 | Add loading/error states and prevent invalid user inputs. | [ ] |
| 24 | Run the complete DApp locally against a test network. | [ ] |
| 25 | Deploy the contract to a testnet and save the deployment address/config. | [ ] |
| 26 | Point the frontend to the deployed testnet contract. | [ ] |
| 27 | Test the complete flow with testnet assets only. | [ ] |
| 28 | Review contract permissions, input validation and transaction edge cases. | [ ] |
| 29 | Polish UI, add network instructions and document contract architecture. | [ ] |
| 30 | Publish the testnet demo and README with setup, contract address and safety notes. | [ ] |

**Final deliverable:** Working testnet crowdfunding DApp.

> **Safety:** Never use real money/private keys for this learning project. Use local development networks and testnets.

---

# 8. Data Science

### Capstone: Sales Analytics & Prediction Dashboard

Build an end-to-end data project: ingest data → clean it → analyze it → visualize it → train a basic model → expose a simple prediction endpoint.

| Day | Practical project task | Done |
|---|---|---|
| 1 | Choose/create a sales dataset and define the questions the project should answer. | [ ] |
| 2 | Load the dataset with Python and inspect columns, types and missing values. | [ ] |
| 3 | Clean obvious formatting/data-quality issues. | [ ] |
| 4 | Use NumPy/Pandas to calculate revenue, orders and basic business metrics. | [ ] |
| 5 | Create reusable data-cleaning functions and save a cleaned dataset. | [ ] |
| 6 | Load the cleaned data into SQL and create the core sales table. | [ ] |
| 7 | Week 1 build: produce a clean dataset + SQL database + basic metrics report. | [ ] |
| 8 | Write SQL queries for sales by date, product and category. | [ ] |
| 9 | Add joins/aggregations to answer multi-table business questions. | [ ] |
| 10 | Use Pandas groupby/merge operations to reproduce key SQL metrics. | [ ] |
| 11 | Create a time-series view of daily/weekly/monthly sales. | [ ] |
| 12 | Create your first charts for revenue and order trends. | [ ] |
| 13 | Add category/product visualizations and identify unusual values. | [ ] |
| 14 | Week 2 build: create a mini analytics report/dashboard from the cleaned data. | [ ] |
| 15 | Define a prediction target and prepare the ML dataset. | [ ] |
| 16 | Split the data into training and testing sets. | [ ] |
| 17 | Train a simple baseline regression model. | [ ] |
| 18 | Evaluate the model with appropriate metrics and record the results. | [ ] |
| 19 | Improve features and train a second model. | [ ] |
| 20 | Compare the models and document what changed. | [ ] |
| 21 | Create a clean prediction function that accepts input data and returns a prediction. | [ ] |
| 22 | Build a small Flask API around the prediction function. | [ ] |
| 23 | Add an API endpoint that accepts JSON and returns the prediction. | [ ] |
| 24 | Test the prediction API with sample requests and invalid inputs. | [ ] |
| 25 | Add a simple frontend/report page that consumes the prediction endpoint. | [ ] |
| 26 | Add visual summaries of model results and important metrics. | [ ] |
| 27 | Add a data/API ingestion step using a public API or scraping workflow where appropriate. | [ ] |
| 28 | Clean the project into reproducible scripts/notebooks and remove unnecessary code. | [ ] |
| 29 | Package the project and prepare a small deployment/demo environment. | [ ] |
| 30 | Ship the final analytics + prediction project with README, dataset description, charts and model results. | [ ] |

**Final deliverable:** End-to-end data science project with analysis, visualization, ML model and simple deployment.

---

#  Weekly Checkpoints

At the end of each week, the project must be usable in some form.

### Week 1
- [ ] Project created
- [ ] Core data/UI/service structure exists
- [ ] First working feature completed
- [ ] Git repository updated

### Week 2
- [ ] Main user flow works
- [ ] Data/state/storage layer started
- [ ] Project can be demonstrated

### Week 3
- [ ] Core technology/framework integrated
- [ ] Realistic data/networking/architecture added
- [ ] Errors and edge cases being handled

### Week 4
- [ ] Capstone completed
- [ ] Tests/checks added
- [ ] UI/UX or developer experience polished
- [ ] Project documented
- [ ] Project deployed or demonstrable

---

#  Daily Log

Copy this for every day:

```text
## Day __

### Built
-

### What changed in the project
-

### Bug/problem I faced
-

### How I fixed it
-

### Git commit
-

### Tomorrow
-
```

---

---

#  The Rule

**Don't finish the 30 days by finishing 30 tutorials.**

Finish the 30 days with **one project that did not exist on Day 1 and actually works on Day 30.**

> **One day = one practical project milestone.**
