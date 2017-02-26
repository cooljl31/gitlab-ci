# A collection of `.gitlab-ci.yml` templates
[![build status](https://gitlab.com/gitlab-org/gitlab-ci-yml/badges/master/build.svg)](https://gitlab.com/gitlab-org/gitlab-ci-yml/commits/master) [![coverage report](https://gitlab.com/gitlab-org/gitlab-ci-yml/badges/master/coverage.svg)](https://gitlab.com/gitlab-org/gitlab-ci-yml/commits/master)

This is GitLabs collection of [`.gitlab-ci.yml`][ci-docs] file templates, to be used
in conjunction with [GitLab CI][gl-ci].
This list is used to populate the `.gitlab-ci.yml` template choosers available
on all GitLab instances running 8.9 or later.

For more information about how `.gitlab-ci.yml` files work, and how to use them,
please read the [documentation on GitLab CI][ci-docs]. Please keep in mind that
these templates might need editing to suit your setup, and should be considered
guideline.

[ci-docs]: http://docs.gitlab.com/ce/ci/
[gl-ci]: https://about.gitlab.com/gitlab-ci/


## Folder structure

The files in the root directory are for `.gitlab-ci.yml` templates that are
project specific, such as language or framework specific templates.
The Pages folder holds `gitlab-ci.yml` templates to be used with [GitLab Pages][gl-pages].

[gl-pages]: http://docs.gitlab.com/ee/pages/README.html

## Contributing guidelines

We’d love you to help us improve this project. To help us keep this collection
high quality, we request that contributions adhere to the following guidelines.

- **Provide a link to the application or project’s homepage**. Unless it’s
  extremely popular, there’s a chance the maintainers don’t know about or use
  the language or framework.

- **Provide links to documentation** supporting the change you’re making. If it's
  possible to provide a link to a successful pipeline on GitLab.com, please 
  provide this.

- **Explain why you’re making a change**. Even if it seems self-evident, please
  take a sentence or two to tell us why your change or addition should happen.
  It’s especially helpful to articulate why this change applies to *everyone*
  who works with the applicable technology, rather than just you or your team.

- **Please only modify *one template* per merge request**. This helps keep merge
  requests and feedback focused on a specific project or technology.

In general, the more you can do to help us understand the change you’re making,
the more likely we’ll be to accept your contribution quickly.

Please also understand that we can’t list every tool that ever existed.
Our aim is to curate a collection of the *most common and helpful* templates,
not to make sure we cover every project possible. If we choose not to
include your language, or framework, it’s not because it’s not awesome.
