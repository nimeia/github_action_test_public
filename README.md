# public-repo-demo

This is the public repository side.

It contains a GitHub Actions workflow that:
1. Starts from the public repository.
2. Uses a dedicated token stored in repository secrets.
3. Checks out the private repository.
4. Runs the private repository packaging script.
5. Uploads the packaging result as an artifact.

## Required secret

- `PRIVATE_REPO_TOKEN`: a token that can read the private repository.

## Required workflow variables

Edit `.github/workflows/package-private-project.yml` and replace:
- `your-org/private-repo-demo`
- `main`

If you prefer, move these to repository variables.
