Repository Conventions
===

### Solving Issues
* Create a new issue on GitHub. Fill in the issue template. Assign the issue to someone.
* Checkout a new branch named `abc_##_description` where `abc` are your initials, `##` is the issue number assigned by GitHub, and `description` is a very brief description of the branch.
* Do not use special characters and in particular no slash characters when naming branches.

### Committing and Pushing
* Work and commit incrementally.
* Commit messages to include an extended description, nominally 100 characters long or longer are permissible to provide detail.
* Push the changes regularly.
   
### Pull Requests
   * When a branch is ready to commit, create a pull request and use the pull request template.
   * Fill in the details of the pull request template. In particular, tag which issues are being fixed by using `fixes ##`, where `##` is the issue number of any issues being fixed. If multiple issues are being fixed, separate the issues with a comma, adding `fixes` for each one of them.
   * Add a meaningful description of the changes. For instance, detail each file that was changed and why it was changed. Provide simple instructions to test whether the changes work.
   * Assign the pull request to a relevant person (either the person who created the issue, or someone who has permissions to merge the branch). Tag relevant people for review, and/or tag people in the pull request description for commenting as needed.
   * Prepend `[WIP]` and/or `[DO NOT MERGE]` if the branch is `Work In Progress` or if the branch should not be merged yet. Remove these flags when no longer needed.
   * Once the branch is merged, the issue it relates to is either closed automatically if it was tagged, or it will be manually closed by the person who merged the branch.
   * The branch may only be deleted if the pull request has indicated this explicitly. If this is the case, the branch will be deleted by the person who merged the branch.
   
### Release Tagging
   * When a new tagged release is to be made, a new issue should be created to request it.
   * This issue should be tagged with appropriate labels, and assigned to someone who can create tagged releases.
   * The tagged release will be created, and the person who did this will then close the issue.
   * The reasons for requesting a new tagged release should be added to the issue description.
   * The person creating the new tag will inspect the pull requests since the last tag, and assess what the semantic version number increment should be for the new tagged release.
   * A brief description for the tagged release should be added. Suggestions can be made in the issue description for the issue that requested the tag, but the previous pull requests should be taken into consideration when naming and describing the new tagged release.
   
### Forking
   * Changes from forked repositories will not be merged into the main repository code.
