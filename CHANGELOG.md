# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.2.0](https://github.com/lotusnoir/ansible-system_hostname/compare/3.1.0...3.2.0) - 2025-11-25

### Commits

- update main to include success flag at the end to be able to monitor last playbook run [`e279c72`](https://github.com/lotusnoir/ansible-system_hostname/commit/e279c723961dfe1eee38f7db01f1482700d9dd4f)

## [3.1.0](https://github.com/lotusnoir/ansible-system_hostname/compare/3.0.0...3.1.0) - 2025-11-17

### Commits

- update core and molecule [`b669939`](https://github.com/lotusnoir/ansible-system_hostname/commit/b6699393dd1f6ad0f8924d0470211d1dec518d3f)
- add oraclelinux10 support + lint and core fixes [`995775e`](https://github.com/lotusnoir/ansible-system_hostname/commit/995775e45022603c04f21d2456c999672cc986cf)

## [3.0.0](https://github.com/lotusnoir/ansible-system_hostname/compare/2.1.0...3.0.0) - 2025-10-29

### Commits

- add trixie (debian13) support [`d0c6058`](https://github.com/lotusnoir/ansible-system_hostname/commit/d0c6058edf39266fa7fdd0b2c4bef405e991cd89)
- update core, molecule + gitlab-ci [`7723a13`](https://github.com/lotusnoir/ansible-system_hostname/commit/7723a133d973b15d282eabf3d09f8738df5af255)
- fix lint [`dcf0a62`](https://github.com/lotusnoir/ansible-system_hostname/commit/dcf0a627398336dcc071eb967c398213449130ff)
- fix molecule paralelism and little updates [`c23bf0c`](https://github.com/lotusnoir/ansible-system_hostname/commit/c23bf0ce54b866058149fbeefa9d0827b115d079)

## [2.1.0](https://github.com/lotusnoir/ansible-system_hostname/compare/2.0.0...2.1.0) - 2025-01-16

### Commits

- add support for ubuntu24 [`e1f09cd`](https://github.com/lotusnoir/ansible-system_hostname/commit/e1f09cdcb341617d6d27018513b40a39788e2448)
- add version on molecule play image to maintain support on old release [`5d99402`](https://github.com/lotusnoir/ansible-system_hostname/commit/5d99402c4723b171a0c518431b06b1d26b7011eb)
- update molecule [`774f669`](https://github.com/lotusnoir/ansible-system_hostname/commit/774f669baa2acf48d8f244e83980d63e667ca044)
- add condition for dbus install and start [`a89df66`](https://github.com/lotusnoir/ansible-system_hostname/commit/a89df668a24f7073b522c0a88e9e85e8010928b1)
- add redhat 9 to default supported distrib [`6f2f3e4`](https://github.com/lotusnoir/ansible-system_hostname/commit/6f2f3e49494955d7cc487bc92c9e77585fb0d0ea)
- add redhat 8 to default supported distrib [`2e3bbe4`](https://github.com/lotusnoir/ansible-system_hostname/commit/2e3bbe4685c83376257404e7394b34e43f2d9fb5)
- sort testing distrib to avoid random changes [`6e4f02a`](https://github.com/lotusnoir/ansible-system_hostname/commit/6e4f02aa175ddc138a8a7d3996e29bf2a543b868)
- update pre-commit and lint fix [`58b4075`](https://github.com/lotusnoir/ansible-system_hostname/commit/58b4075a2264f1dcabea5dd5427af896de54107c)
- remove rhel7 support and remove docker dind on pipeline [`e910a7d`](https://github.com/lotusnoir/ansible-system_hostname/commit/e910a7db20a2377b121f7c134e7d7137918453a9)
- remove lint from pipeline [`a5423e7`](https://github.com/lotusnoir/ansible-system_hostname/commit/a5423e7b0819b03625e68c00c38017fb27fac859)

## [2.0.0](https://github.com/lotusnoir/ansible-system_hostname/compare/1.1.0...2.0.0) - 2023-09-25

### Commits

- update vars [`f9812c3`](https://github.com/lotusnoir/ansible-system_hostname/commit/f9812c3dcf489e981c3eaa247ee0183edbf5961b)
- update readme + precommit + include vars [`9677313`](https://github.com/lotusnoir/ansible-system_hostname/commit/96773130b1ab8c2992116ae96a47516197ae110d)
- change import tasks to include in order to support facts on name [`822a0db`](https://github.com/lotusnoir/ansible-system_hostname/commit/822a0db62d3304e18ac7e570cb2257552f1b2db2)

## [1.1.0](https://github.com/lotusnoir/ansible-system_hostname/compare/1.0.0...1.1.0) - 2023-06-14

### Commits

- add debian12 support [`0dcdf81`](https://github.com/lotusnoir/ansible-system_hostname/commit/0dcdf8115c407bff7de8ab0b0e0562a51e275145)

## [1.0.0](https://github.com/lotusnoir/ansible-system_hostname/compare/0.2.0...1.0.0) - 2023-03-23

### Commits

- add code of conduc and small changes [`746f428`](https://github.com/lotusnoir/ansible-system_hostname/commit/746f428e43537c2bcebdf40cc6e2834752513ca2)
- add precommit for lint [`be95869`](https://github.com/lotusnoir/ansible-system_hostname/commit/be958691e57f62d4d8e1f34003321135d1661605)
- fix checks [`db4316b`](https://github.com/lotusnoir/ansible-system_hostname/commit/db4316b3c3efc3e6c6862596fd7ae8a7b348d67e)
- reduce checks with assert [`0da2c3a`](https://github.com/lotusnoir/ansible-system_hostname/commit/0da2c3ab9565b885c4295204ba1d03c950d1e0f3)
- add new molecule all scenario [`b94f443`](https://github.com/lotusnoir/ansible-system_hostname/commit/b94f4437371eb9e358c9ff9b13fd9e6ee22417ed)
- split distro for molecule tests on ci [`8c67911`](https://github.com/lotusnoir/ansible-system_hostname/commit/8c679112a2d842c49bcde4f6cf78ccab6b501d54)
- update checks and Readme [`9438a89`](https://github.com/lotusnoir/ansible-system_hostname/commit/9438a898b44a89c7d94de3493970bd3a3862cf4a)
- add molecule fix for ora9 [`787fb09`](https://github.com/lotusnoir/ansible-system_hostname/commit/787fb091beac0ea555e0f9a9bf122a207272f3c2)
- add ora9 support [`03a5e0f`](https://github.com/lotusnoir/ansible-system_hostname/commit/03a5e0f0386de80d5df0bec0c7e807f448c2947b)
- fix lint [`a4bd80b`](https://github.com/lotusnoir/ansible-system_hostname/commit/a4bd80b6062639b22cc84bd0d5841df5b6adb947)

## [0.2.0](https://github.com/lotusnoir/ansible-system_hostname/compare/0.1.0...0.2.0) - 2022-07-01

### Commits

- minor: add oracleLinux7 support [`aeee30a`](https://github.com/lotusnoir/ansible-system_hostname/commit/aeee30addf2453442725e4620ca995f0d21cdd45)
- minor: add oracleLinux support + little fixes [`f94246c`](https://github.com/lotusnoir/ansible-system_hostname/commit/f94246cc9ab1c4659f3067a89b0d41bf4d36ac47)

## 0.1.0 - 2022-06-02

### Commits

- minor: add ubuntu 22 molecule test + fix lint [`5a0d348`](https://github.com/lotusnoir/ansible-system_hostname/commit/5a0d348903230e1ad1354c2d04aac867eb1e3aa1)
- fix: remove unsupported centos8 + minor fixes [`1c96cfa`](https://github.com/lotusnoir/ansible-system_hostname/commit/1c96cfa98802c9e2be75c80350aa8c6a377b273b)
- fix: probleme on molecule to fix later [`727371b`](https://github.com/lotusnoir/ansible-system_hostname/commit/727371b462b2aff2d73c43e7c982b94cc48744ee)
- initial commit [`84ef0aa`](https://github.com/lotusnoir/ansible-system_hostname/commit/84ef0aa15573b9d1c96f83b5d4dfb41344bbdad4)
