<header>

<!--
  <<< Author notes: Course header >>>
  Read <https://skills.github.com/quickstart> for more information about how to build courses using this template.
  Include a 1280×640 image, course name in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Next to "About", add description & tags; disable releases, packages, & environments.
  Add your open source license, GitHub uses the MIT license.
-->

# Enable CodeQL to secure your source code

_Ensuring the security of application source code is a critical step in modern software development. In this GitHub Skills course, you will learn to use GitHub code scanning to identify, resolve, and prevent insecure coding patterns._

</header>

<!--
  <<< Author notes: Finish >>>
  Review what we learned, ask for feedback, provide next steps.
-->

## Finish

_Congratulations! You have completed this course!_ 🏆

Here's a recap of all the tasks you accomplished in your repository:
  - Enabled CodeQL on your repository.
  - CodeQL scanned the code in your repository and notified us of two SQL injection vulnerabilities.
  - Reviewed the findings, marked the findings as closed, and explored the audit trail.
  - Fixed your code in the main branch and saw that the findings automatically closed out.
  - Introduced a new vulnerability in a new branch.
  - Created a pull request, and were notified of the vulnerability.

### What's next?

- Continue your learning! Our [code scanning documentation](https://docs.github.com/en/code-security/code-scanning/automatically-scanning-your-code-for-vulnerabilities-and-errors/about-code-scanning) is a great resource for learning more about CodeQL.
- Learn more about CodeQL. Take a look at the [CodeQL documenation](https://codeql.github.com/docs/) site to learn about all of the features of this powerful tool.
- [We'd love to hear what you thought of this course](https://github.com/orgs/skills/discussions/405).
- [Take another Skills course.](https://github.com/skills).
- [Read the GitHub Getting Started docs](https://docs.github.com/en/get-started).
- To find projects to contribute to, check out [GitHub Explore](https://github.com/explore).

### :keyboard: Activity 3: Create a pull request

In this activity, we'll create a pull request to merge the new branch with the insecure code into the `main` branch.

1. Navigate to the **Pull requests** tab in your repository.
2. Click the **New pull request** button.
3. Select the new branch you created in the previous activity from the dropdown menu.
4. Click the **Create pull request** button.
5. Add a title and description for your pull request.
6. Click the **Create pull request** button again to submit the pull request.

### :keyboard: Activity 4: Review the pull request

Now that we've created the pull request, let's review it to see the experience of identifying the introduced vulnerability.

1. In the **Pull requests** tab, click on the pull request you just created.
2. Scroll down to the **Checks** section and look for the "Code scanning/CodeQL" check.
3. Once the check is complete, you will see a comment from CodeQL indicating a new security vulnerability.
4. Review the data flow paths by clicking **Show paths**.
5. Add a comment and tag one of your friends by using their GitHub handle (example: `@username`).

### :keyboard: Activity 5: Merge the pull request

In this final activity, we'll merge the pull request to complete the process.

1. In the **Pull requests** tab, click on the pull request you just reviewed.
2. Click the **Merge pull request** button.
3. Confirm the merge by clicking the **Confirm merge** button.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/introduction-to-codeql) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
