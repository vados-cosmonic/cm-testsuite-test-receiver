# cm-testsuite test receiver

A minimal receiving repository for trying out
[cm-testsuite](https://github.com/vados-cosmonic/cm-testsuite).

`.cm-testsuite.toml` only enables receiving:
catalog tests that need only `component-model` are accepted under `tests/shared/`,
proposed as one draft pull request.
No tests are shared from here.

`.github/chainguard/cm-testsuite.sts.yaml` lets cm-testsuite's workflows open that pull request.
