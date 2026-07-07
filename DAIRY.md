### 05.07.2026

To protect main branch from direct pushes, added branch rule that disables direct pushes to main branch. Now, all changes must go through pull requests and be reviewed before merging.

Very simple implementation, the differance between other action is that this action is configured on GitHub repository settings, not in the workflow file.

### 05.07.2026

Created my new workflow file that check feature branch name. All the branches should start with "feature/" prefix. If the branch name does not follow this rule, the workflow will fail and prevent merging.

### 05.07.2026

Create my second workflow that works on every push to the branch. This workflow is CI part of CI/CD pipeline. It runs linters, test and build the project. If any of these steps fail, the workflow will fail and prevent merging.

### 06.07.2026

The last workflow that I created is the CD part of CI/CD pipeline. It runs when a pull request is created or updated. It deploys the project to the staging environment. If the deployment fails, the workflow will fail and prevent merging.

### 06.07.2026

Can't implement other part of the task because when I deploy the project and tru to access it, I get only html representation of the project. I GitHub Pages is a static site hosting service, it does not support server-side rendering or dynamic content. Therefore, I can't deploy my project to GitHub Pages and access it as a dynamic web application. I need to find another hosting service that supports server-side rendering and dynamic content.

May be I can't find a solution to this problem because I don't have enough knowledge about hosting services. I need to learn more about hosting services and how to deploy a project that requires server-side rendering and dynamic content.
