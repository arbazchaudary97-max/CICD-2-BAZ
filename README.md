## Task 1: Basic CI Pipeline

For Task 1, I created a basic CI pipeline using GitHub Actions.

The workflow is stored in:

.github/workflows/ci.yaml

The pipeline runs automatically whenever changes are pushed to the main branch.

### What the CI pipeline does

The workflow performs basic checks to confirm that important project files exist and that the repository structure is correct.

### Trigger

The workflow is triggered on push to the main branch.

### Evidence

The workflow was tested by committing and pushing changes to GitHub. The GitHub Actions tab shows the workflow running successfully.

### Issues Faced

During this task, I had issues with the workflow file being in the wrong folder. I fixed this by moving the workflow to the correct GitHub Actions folder:

.github/workflows/