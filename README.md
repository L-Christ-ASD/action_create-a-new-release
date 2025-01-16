# action_create-a-new-release

![just debug steps of execution](https://github.com/L-Christ-ASD/action_create-a-new-release/actions/workflows/nodejs_release.yml/badge.svg)

To automatically create a new GitHub release when tags are pushed to the repository

**How it Works:**

**Trigger:** The workflow is triggered whenever a tag matching the pattern v*.*.* is pushed.

**Checkout Code:** The workflow checks out the code from the repository.

**Set Up Node.js:** It sets up Node.js(adjust the version if needed).

**Install Dependencies:** It installs the required dependencies.

**Run Tests:** It runs the tests to ensure everything is working correctly.

**Create Release:** It creates a new release with the tag.

**Upload Release Asset:** If you have any release assets (e.g., compiled binaries), you can upload them.  


*Feel free to customize the workflow to fit your project's needs.*