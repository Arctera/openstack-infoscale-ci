# InfoScale Cinder Driver — CI Test Logs

This repository hosts the CI test logs for the
**InfoScale OpenStack Cinder Driver**.

## Purpose

The [OpenStack Third-Party CI guidelines](https://docs.openstack.org/infra/system-config/third_party.html)
require every third-party Cinder driver to operate a Continuous Integration
pipeline that:

1. Runs the **Cinder Tempest test suite** against each proposed patch.
2. Publishes the resulting logs in a publicly accessible location so that
   community code-reviewers can verify test outcomes.

This repository fulfils requirement (2). Each CI run uploads its log artifacts
here, providing full test results of the InfoScale Cinder Driver.

## What You Will Find Here

- **Consolidated test results** — pass/failure status for each Tempest test
  case executed during the CI run.
- **Tempest test logs** — detailed stdout/stderr output from `tempest run`
  executions.
- **Cinder service logs** — logs from `cinder-volume`, `cinder-api`,
  `cinder-scheduler`, and related services captured during each test run.

## About InfoScale Cinder Driver

The InfoScale Cinder Driver integrates
[InfoScale](https://infoscale.com/) storage with OpenStack Block Storage
(Cinder), enabling volume provisioning, snapshots, and cloning on
InfoScale-managed storage.

## License

This repository contains CI log artifacts only and is provided for
informational and review purposes.

