# GitHub Actions label-gate semantics test

Controlled reproduction of a label-gated `pull_request_target` workflow.
Tests whether a later label event re-runs the workflow against a commit pushed AFTER the approving label was applied.
Owned test repository; no third-party systems involved.
