# CHANGELOG - Cilium

## 1.5.0 / 2020-10-31

* [Added] Sync openmetrics config specs with new option ignore_metrics_by_labels. See [#7823](https://github.com/DataDog/integrations-core/pull/7823).
* [Added] Add ability to dynamically get authentication information. See [#7660](https://github.com/DataDog/integrations-core/pull/7660).

## 1.4.0 / 2020-09-21 / Agent 7.23.0

* [Added] Add RequestsWrapper option to support UTF-8 for basic auth. See [#7441](https://github.com/DataDog/integrations-core/pull/7441).
* [Fixed] Do not render null defaults for config spec example consumer. See [#7503](https://github.com/DataDog/integrations-core/pull/7503).
* [Fixed] Update proxy section in conf.yaml. See [#7336](https://github.com/DataDog/integrations-core/pull/7336).

## 1.3.0 / 2020-08-10 / Agent 7.22.0

* [Added] Add config specs. See [#7319](https://github.com/DataDog/integrations-core/pull/7319).

## 1.2.0 / 2020-05-17 / Agent 7.20.0

* [Added] Add environment runner for Kubernetes' `kind`. See [#6522](https://github.com/DataDog/integrations-core/pull/6522).
* [Added] Allow optional dependency installation for all checks. See [#6589](https://github.com/DataDog/integrations-core/pull/6589).

## 1.1.0 / 2020-04-04 / Agent 7.19.0

* [Added] Add Cilium version metadata. See [#5408](https://github.com/DataDog/integrations-core/pull/5408).
* [Fixed] Update deprecated imports. See [#6088](https://github.com/DataDog/integrations-core/pull/6088).

## 1.0.2 / 2020-01-13 / Agent 7.17.0

* [Fixed] Remove unused variables. See [#5173](https://github.com/DataDog/integrations-core/pull/5173).

## 1.0.1 / 2019-12-06 / Agent 7.16.1

* [Fixed] Raise configuration errors. See [#5163](https://github.com/DataDog/integrations-core/pull/5163).

## 1.0.0 / 2019-11-19

* [Added] New Integration: Cilium. See [#4665](https://github.com/DataDog/integrations-core/pull/4665).
