# GitHub Pull Request Status Test

This repository only exists to replicate [a GitHub bug](https://github.com/kevin-brown/github-support-tickets/issues/1) involving status checks on Pull Requests. It should only be triggered if the pull request is created on a repository within an organization, but not for individual accounts.

This requires that status checks are enabled, and that there is a valid status check set up for the pull request. It does not happen if there are no status checks set up.
