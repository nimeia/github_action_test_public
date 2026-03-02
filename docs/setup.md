# Setup

1. Create a public GitHub repository.
2. Copy the contents of `public-repo-demo/` into it.
3. Create a private GitHub repository.
4. Copy the contents of `private-repo-demo/` into it.
5. In the public repository settings, add a repository secret named `PRIVATE_REPO_TOKEN`.
6. Make sure the token can read the private repository contents.
7. Update the workflow file so `PRIVATE_REPO` matches your private repository.
8. Trigger the workflow with `workflow_dispatch`.
