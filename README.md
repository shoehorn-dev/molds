# Shoehorn Molds
This repository demonstrates workflow templates (molds) which can be used by the Shoehorn platform.

## 📦 Available Molds

### Create GitHub Repository
**File:** `create-github-repo.json`
**Purpose:** Create a new GitHub repository with customizable settings

**Inputs:**
- `name` (required) - Repository name (lowercase, alphanumeric with dashes)
- `description` - Repository description
- `defaultBranch` - Default branch name (main, master, or develop)
- `autoInit` - Initialize repository with README (default: true)
- `private` - Create as private repository (default: true)
- `hasIssues` - Enable issues (default: true)
- `hasWiki` - Enable wiki (default: false)
- `hasProjects` - Enable projects (default: false)

**Outputs:**
- `repositoryUrl` - GitHub API URL
- `htmlUrl` - GitHub web URL
- `cloneUrl` - HTTPS clone URL
- `sshUrl` - SSH clone URL
