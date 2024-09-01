# CI pipeline

### Project goals
1. To integrate with version control system.
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
- **User story 3**: As a developer, I want a decision on when to trigger the CI pipeline e.g push and pull request triggers.
- **User story 4**: As a developer, I want a decision on setting up manual triggers for certain branches (e.g., production) to ensure careful control over what gets built and deployed.
- **User story 5**: As a developer, I want to ensure that I'm authorized to trigger builds, merge code, and push to critical branches i.e role-based access controls.
- **User story 6**: As a developer, I want any tokens, credentials, or secrets used by the CI pipeline (e.g., for deployment or accessing third-party services) safeguarded using tools like GitHub Secrets.
- **User story 7**: As a developer, I want an enforcement of meaningful and standardized commit messages that help in tracking changes and understanding the history of the codebase.
- **User story 8**: As a developer, I want an enforcement of code formatting, linting, or other checks before code is committed to the repository using pre-commit hooks to prevent trivial errors from entering the CI pipeline.
- **User story 9**: As a developer, I want CI configuration files (e.g.  `.github/workflows/`) stored in the version control system itself to ensure that the CI configuration is versioned alongside the code.
- **User story 10**: As a developer, I want to ensure that the CI configuration can handle different environments (e.g., development, staging, production) by parameterizing environment-specific settings.
- **User story 11**: As a developer, I want an enforcement of code reviews via pull requests to catch issues early, before code is merged into critical branches so that only high-quality code reaches the main branch.
- **User story 12**: As a developer, I want to ensure the CI is configured to only build and test the parts of the codebase that were changed, rather than the entire project because of using a monorepo, to save time and resources.
- **User story 13**: As a developer, I want parallelization in the CI pipeline, for example, run different test suites or build processes concurrently to speed up the process.
- **User story 14**: As a developer, I want to ensure that build artifacts (e.g., compiled binaries) are stored securely and are versioned appropriately to ensure reproducibility and rollback.
- **User story 15**: As a developer, I want to use a consistent naming convention for artifacts, including version numbers, commit hashes, or build numbers, to easily track and identify them.
- **User story 16**: As a developer, I want to receive notifications (e.g., via Slack, email) to inform me about the status of builds, tests, and deployments and ensure that notifications are actionable and not overwhelming.
- **User story 17**: As a developer, I want to see status badges in the repository’s README file to show the current status of the CI pipeline for key branches.
- **User story 18**: As a developer, I want to be quickly notified when a build fails as this allows me to address issues promptly and maintain the flow of development.
- **User story 19**: As a developer, I want an automated process of reverting commits that cause build failures, especially in critical branches like `production`.
- **User story 20**: As a developer, I want a record of who pushed what code and who approved which pull requests so as to ensure accountability and regulatory compliance.
- **User story 21**: As a developer, I want static code analysis tools integrated in the CI pipeline to catch security vulnerabilities, code smells, and other issues early in the development process.
- **User story 22**: As a developer, I want a regularly backed up version control system to ensure that code history and branches are safe in case of hardware failure or other issues.
- **User story 23**: As a developer, I want to ensure that the CI configuration and related scripts are backed up.
- **User story 24**: As a developer, I want a documented CI/CD process, including how the CI system is integrated with the VCS, how to trigger builds, and how to troubleshoot common issues.
- **User story 25**: As a new developer, I want clear instructions for me on how to work with the CI and version control systems, including any required setup steps.

**Acceptance Criteria:**
- [ ] Criterion 1: The CI pipeline must automatically trigger a build whenever there is a new commit to the designated branches (e.g., `production`, `development`, `features` branches).
- [ ] Criterion 2: Different branches (e.g., `production`, `development`, `features` branches) must trigger the appropriate CI pipeline workflows. For example, the main branch triggers a full build and deployment process, while feature branches trigger build and test pipelines.
- [ ] Criterion 3: 




