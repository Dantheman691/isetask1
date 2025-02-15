# isetask1
# README: Branching and Merging Strategy for SDLC Analysis of Amazon

## Repository Overview
This repository contains the Software Development Lifecycle (SDLC) analysis for Amazon, focusing on a comparative study of different process models and their impact on requirements management. The repository includes initial and revised versions of the requirements document along with a structured branching strategy to manage changes efficiently.

## Branching Strategy
The branching model used follows a structured approach to ensure organized development, maintain version control, and enable efficient collaboration. The key branches in the repository are:

### 1. **Main Branch**
   - The stable version of the report and requirements document is maintained here.
   - Only reviewed and finalized changes are merged into this branch.
   - Used for official submission and final documentation.

### 2. **Feature Branches**
   - Each major update or modification is developed in a separate feature branch.
   - Feature branches are created from the `main` branch and named according to the feature being implemented, e.g., `feature-requirements-update`.
   - These branches allow iterative improvements without disrupting the main document.

### 3. **Development Branch**
   - Acts as an intermediate branch for integrating multiple feature updates.
   - Feature branches are merged here first before merging into `main`.
   - Used for testing and reviewing content before final approval.

## Merging Strategy
To maintain consistency and avoid conflicts, the following merging strategy is followed:

1. **Pull Request (PR) Workflow:**
   - Feature branches submit pull requests to the `development` branch.
   - Changes are reviewed by collaborators before merging.
   - Feedback is incorporated before approval.

2. **Testing and Validation:**
   - Changes in the `development` branch are tested for accuracy and completeness.
   - Reviews are conducted to ensure consistency with project objectives.

3. **Merging to Main:**
   - Once reviewed and tested, changes in the `development` branch are merged into `main`.
   - A final validation is performed before deployment.

## Version Control Best Practices
- **Commit Messages:** Each commit message follows a structured format describing the changes made.
- **Regular Updates:** Feature branches are frequently updated with changes from `main` to prevent merge conflicts.
- **Backup Strategy:** Snapshots of critical changes are maintained to ensure recovery if needed.

## Repository Link
Access the repository here: [GitHub Repository](https://github.com/Dantheman691/isetask1/tree/main)

This strategy ensures a structured approach to document versioning, enabling smooth collaboration and maintaining a clean project history.


