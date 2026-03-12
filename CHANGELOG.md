Changelog of GitHub Workflow Immortality
========================================

### Version 1.2.0
Released: 2026-03-12

* [[#5]](https://github.com/PhrozenByte/gh-workflow-immortality/pull/5) Add `--no-repo-names` CLI option resp. `no_repo_names` GitHub action option to suppress printing repository names; additionally always print repository IDs [[0cbc7f6]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/0cbc7f6) [[cc0c197]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/cc0c197) [[afe1233]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/afe1233) [[8c1ebe0]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/8c1ebe0)
* Add `verbose` GitHub action option to enable the `--verbose` CLI option [[1de4712]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/1de4712)
* Improve compatibility with BSD utilities [[e07d0f0]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/e07d0f0) [[9e1a6d6]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/9e1a6d6) [[66125f7]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/66125f7) [[e108627]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/e108627) [[697d8a5]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/697d8a5)
* Fix handling of multi-page API responses [[1a4c561]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/1a4c561)
* Fix GitHub API rate limit checks [[f39c061]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/f39c061) [[773b006]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/773b006)
* Various small improvements [[a8def4a]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/a8def4a) [[e1f3c71]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/e1f3c71) [[b694373]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/b694373)

### Version 1.1.3
Released: 2025-08-24

* [[#3]](https://github.com/PhrozenByte/gh-workflow-immortality/pull/3) Trim environment variables before usage to support GitHub Action variables [[85f28bb]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/85f28bb)
* Various small improvements [[febd188]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/febd188) [[031c085]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/031c085)

### Version 1.1.2
Released: 2025-05-06

* Properly handle HTTP redirects and partial GitHub API responses [[eff45ae]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/eff45ae)
* Check and document `awk` script dependency [[176fb51]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/176fb51)

### Version 1.1.1
Released: 2025-03-04

* Fix usage of 'REPO' env variable [[a55e781]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/a55e7812491ec2fd8e8a047e7af9790f4ef0de53)
* Various small improvements [[6a65ea0]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/6a65ea076da34c7d4990ddb7d9db558cbf32477f)

### Version 1.1.0
Released: 2025-03-04

* Refactor functions to use return variables instead [[a58ce23]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/a58ce230acc45e2d7434eb85d61282d1b11a37f0)
* Add `--verbose` option to print a list of issued GitHub API requests [[f6c8bd3]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/f6c8bd39c2cbdb3b58ba211db2d8c34c0cbb3f1f)
* Respect GitHub's API rate limit [[5630517]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/56305170000d0bb8d2cf40e2bf4e807f6c9eb641)
* Add `--forks` option to also load forked repositories [[6cbccc4]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/6cbccc4917f4f3286b1d577083ffb70ec441a93f)
* [[#1]](https://github.com/PhrozenByte/gh-workflow-immortality/issues/1) Exclude workflows not matching '.github/workflows/*' [[a274dce]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/a274dce7f5ffc7820c54dc305d0c39e9b5e3741f)
* Various small improvements [[fd10aa4]](https://github.com/PhrozenByte/gh-workflow-immortality/commit/fd10aa441c755e4c72b23a306c26c0633fe187df)

### Version 1.0.0
Released: 2023-01-19

* Initial public release
