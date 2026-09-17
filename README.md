# keras-rs-ci

Runs the keras-rs test suite against a branch of
[Nicholas022400701/keras-rs](https://github.com/Nicholas022400701/keras-rs)
on GitHub hosted runners, for the tensorflow, jax and torch backends.
The upstream workflow uses self hosted runners that a fork does not have,
so this repo mirrors its CPU test and format check jobs.

Trigger it from the Actions tab with the branch name, or push to main.
From the CLI:

```
gh workflow run keras_rs_tests.yml -R Nicholas022400701/keras-rs-ci -f ref=<branch>
```
