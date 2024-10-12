# run-in-container

GitHub Actions is deficient and buggy.

Jobs can run in containers, but common actions like checkout or upload-artefact require nodejs to run in the container, which isn't always possible.
There is no built-in capability to run a a single step in a container, so this action provides that.

This is not really for general purpose use and would be better kept in the repo with the workflow that uses it,
but actions runner are intermittently unable to find actions in the same repo, so it's easier to keep it in a separate repo.
