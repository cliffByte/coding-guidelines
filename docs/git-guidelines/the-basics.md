---
sidebar_position: 1
---

# The Basics

Before getting started with the git, we will be always using **git-flow** with git.

To setup **git-flow**; first intialize git project ; and then intialize git flow using following command;<br/>
`git flow init`
and, free enter for the **git-flow** default settings.

<hr/>

### Important Notes.

    Developers must not work on the master branch; unless said or required. And,
    shouldn’t push any Commit to master. (for developers, commits are always meant
    to be done on the develop or other branches).

    Developers must not create any unrequired branches , and should always follow
    the convention for creating the branch.

    During the project work-flow, the project manager should always make sure
    the projects are up to date in the dev/develop branch, and before working
    on the project, developers must always pull the project from the origin,
    and then begin to work.

    After the completion of the project, the project should be merged to the
    master or production branch by the project manager. The developer shall
    not migrate the develop branch code to the new branch until and unless
    allowed by the Project Manager. The new branch name will be the version of
    the project (i.e. v1, v2 branches) and for the next update, the work will
    be again done in the develop branch.

### The Fundamentals

- Before working on project, make sure to git pull the latest changes (if any).
- Our production Code will always remain in the master(main) branch.
- For the development(working) process, developers will always work in the dev/develop branch.
  In the develop branch; when developer work on feature, one should create respective feature branch with the following convention:

      feature/feature_name
      Example : feature/login_ui, feature/login_api_integration.

Once the feature is done, then it is merged to the dev/develop branch.
