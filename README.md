### Java Spring template project

This project is based on a GitLab [Project Template](https://docs.gitlab.com/ee/gitlab-basics/create-project.html).

Improvements can be proposed in the [original project](https://gitlab.com/gitlab-org/project-templates/spring).

### CI/CD with Auto DevOps

This template is compatible with [Auto DevOps](https://docs.gitlab.com/ee/topics/autodevops/).

If Auto DevOps is not already enabled for this project, you can [turn it on](https://docs.gitlab.com/ee/topics/autodevops/#enabling-auto-devops) in the project settings.
# link url article

> https://docs.gitlab.com/ee/ci/examples/deploy_spring_boot_to_cloud_foundry/index.html

# Install Runner
>  https://docs.gitlab.com/runner/install/linux-manually.html
# Register Runner
> https://docs.gitlab.com/runner/register/index.html
# Fix bug 

> https://gitlab.com/gitlab-org/gitlab-runner/issues/3750

> https://gitlab.com/gitlab-org/gitlab-runner/issues/2831

> https://medium.com/@jonathanborges/new-runner-has-not-connected-yet-b6fc6ce50e4e

> https://stackoverflow.com/questions/42968814/how-to-make-the-activated-specific-runner-of-gitlab-working

#  Untility commands

> gitlab-runner --debug run

> sudo gitlab-runner stop

# More
> https://viblo.asia/p/phan-1-gioi-thieu-ve-kubernetes-924lJO6m5PM

gitlab-runner register --non-interactive --executor 'shell' --url 'https://gitlab/' --registration-token 'token'
