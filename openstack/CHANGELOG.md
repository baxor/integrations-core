# CHANGELOG - openstack

## 1.13.0 / 2022-04-05 / Agent 7.36.0

* [Added] Add metric_patterns options to filter all metric submission by a list of regexes. See [#11695](https://github.com/DataDog/integrations-core/pull/11695).

## 1.12.0 / 2022-02-19 / Agent 7.35.0

* [Added] Add `pyproject.toml` file. See [#11408](https://github.com/DataDog/integrations-core/pull/11408).
* [Fixed] Fix namespace packaging on Python 2. See [#11532](https://github.com/DataDog/integrations-core/pull/11532).

## 1.11.1 / 2021-10-04 / Agent 7.32.0

* [Fixed] Add server as generic tag. See [#10100](https://github.com/DataDog/integrations-core/pull/10100).

## 1.11.0 / 2021-04-19 / Agent 7.28.0

* [Added] Openstack log support. See [#9116](https://github.com/DataDog/integrations-core/pull/9116).
* [Fixed] Include missing default config templates. See [#9150](https://github.com/DataDog/integrations-core/pull/9150).

## 1.10.3 / 2021-03-07 / Agent 7.27.0

* [Fixed] Bump minimum base package version. See [#8443](https://github.com/DataDog/integrations-core/pull/8443).

## 1.10.2 / 2020-09-21 / Agent 7.23.0

* [Fixed] Fix style for the latest release of Black. See [#7438](https://github.com/DataDog/integrations-core/pull/7438).

## 1.10.1 / 2020-06-29 / Agent 7.21.0

* [Fixed] Use agent v6 init signature. See [#6830](https://github.com/DataDog/integrations-core/pull/6830).

## 1.10.0 / 2020-05-17 / Agent 7.20.0

* [Added] Allow optional dependency installation for all checks. See [#6589](https://github.com/DataDog/integrations-core/pull/6589).

## 1.9.1 / 2020-04-04 / Agent 7.19.0

* [Fixed] Update deprecated imports. See [#6088](https://github.com/DataDog/integrations-core/pull/6088).

## 1.9.0 / 2020-01-13 / Agent 7.17.0

* [Added] Use lazy logging format. See [#5398](https://github.com/DataDog/integrations-core/pull/5398).
* [Added] Use lazy logging format. See [#5377](https://github.com/DataDog/integrations-core/pull/5377).

## 1.8.3 / 2019-10-11 / Agent 6.15.0

* [Fixed] Fix documented default for `use_agent_proxy`. See [#4517](https://github.com/DataDog/integrations-core/pull/4517).

## 1.8.2 / 2019-08-24 / Agent 6.14.0

* [Fixed] Use utcnow instead of now. See [#4192](https://github.com/DataDog/integrations-core/pull/4192).

## 1.8.1 / 2019-06-01 / Agent 6.12.0

* [Fixed] Fix code style. See [#3838](https://github.com/DataDog/integrations-core/pull/3838).
* [Fixed] Sanitize external host tags. See [#3792](https://github.com/DataDog/integrations-core/pull/3792).

## 1.8.0 / 2019-05-14

* [Added] Adhere to code style. See [#3550](https://github.com/DataDog/integrations-core/pull/3550).

## 1.7.0 / 2019-02-18 / Agent 6.10.0

* [Added] Support Python 3. See [#3035](https://github.com/DataDog/integrations-core/pull/3035).

## 1.6.0 / 2019-01-04 / Agent 6.9.0

* [Added] Adds ability to Trace "check" function with DD APM. See [#2079](https://github.com/DataDog/integrations-core/pull/2079).

## 1.5.0 / 2018-08-29 / Agent 6.5.0

* [Fixed] Remove duplicate project call and reword os_host config option. See [#2066](https://github.com/DataDog/integrations-core/pull/2066).
* [Fixed] Use is_affirmative on boolean options. See [#2071](https://github.com/DataDog/integrations-core/pull/2071).

## 1.4.0 / 2018-08-17

* [Fixed] Only use the short hostname when making "host" queries to Nova. See [#2070](https://github.com/DataDog/integrations-core/pull/2070).
* [Changed] Add data files to the wheel package. See [#1727](https://github.com/DataDog/integrations-core/pull/1727).

## 1.3.0 / 2018-06-06

* [Added]  Added support for unscoped access, implemented caching mechanism to reduce API calls to Nova. See [#1276](https://github.com/DataDog/integrations-core/pull/1276).

## 1.2.0 / 2018-05-11

* [FEATURE] Add custom tag support to service check and metrics.

## 1.1.0 / 2018-02-28

* [BUGFIX] Properly disable the Agent's proxy settings when desired. See [#1123](https://github.com/DataDog/integrations-core/issues/1123)
* [IMPROVEMENT] Adds parameter to collect metrics on all projects in a domain. See [#1119](https://github.com/DataDog/integrations-core/issues/1119)
* [IMPROVEMENT] Added support for Agent >= 6.0. See [#1126](https://github.com/DataDog/integrations-core/issues/1126)

## 1.0.2 / 2017-11-21

* [IMPROVEMENT] Don't check on powered off VMs. See [#878](https://github.com/DataDog/integrations-core/issues/878)

## 1.0.1 / 2017-08-28

* [IMPROVEMENT] Adds human friendly "project_name" tag in all cases. See [#515](https://github.com/DataDog/integrations-core/issues/515)

## 1.0.0 / 2017-03-22

* [FEATURE] adds openstack integration.
