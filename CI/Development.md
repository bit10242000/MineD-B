# CI pipeline

### Project goals
1. To develop integration with version control system.
2. To develop automated testing.
3. To develop code quality checks.
4. To develop build automation.

### Stakeholders
1. :scrum master
2. : developer

### Features list 
1. Integration with version control system.

   When changes are pushed to the repository, the CI pipeline is triggered.
2. Automated testing.

   Every time code is committed to the repository, it triggers automated tests to ensure the code works as expected. This can include unit tests, integration tests, and more.
3. Code quality checks.

   Integrate into the CI pipeline to enforce coding standards and detect potential bugs, tools like SonarQube or ESLint.
4. Automated builds.

   The code is automatically built into executable files or packages, ready for deployment.


### Feature 1: Integration with version control system.

**Description:**
Areas include consistent Branching Strategy, CI pipeline efficiency, CI pipeline trigger, access control and permissions, commit hygiene and automation, CI configuration management, code reviews, artifact management, notifications and reporting, handling failed builds, compliance and security, backup and recovery, and Documentation. 

**User stories:**
- **User Story 1**: As a developer, I want to have a clear and consistent branching strategy (e.g. GitHub Flow) so as to ensure that the CI pipeline knows which branches to monitor, build, and deploy.
- **User story 2**: As a developer, I want to ensure the CI system can handle builds and tests efficiently across multiple projects within the same repository because of using a monorepo.
- **User story 3**: As a developer, I want a decision about when to trigger the CI pipeline e.g push and pull request triggers.
- **User story 4**: As a developer, I want to 

**Acceptance Criteria:**
- [ ] Criterion 1: The 
