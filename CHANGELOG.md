# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed

- Push to `capa-app-collection`, `cloud-director-app-collection` and `vsphere-app-collection`.

## [0.4.2] - 2022-06-13

### Changed

- Push to `openstack-app-collection`.

## [0.4.1] - 2021-09-03

### Fixed

- Fix Ingress api version.

## [0.4.0] - 2021-09-02

### Changed

- Move `ServiceMonitor.spec.metricRelabelings` out to config to avoid enforcing
  PII redacting onto all chart users.

## [0.3.0] - 2021-08-19

### Added

- Add support for overriding server args through Helm values.

## [0.2.1] - 2021-08-19

### Fixed

- Add missing labeling schema to service monitor.

## [0.2.0] - 2021-08-12

### Added

- Add Ingress auth using Grafana authentication.
- Add ServiceMonitor for Prometheus scrape to take place.

### Changed

- Restrict ingress to /write

## [0.1.1] - 2021-07-29

### Changed

- Regress ingress to v1beta1.

## [0.1.0] - 2021-07-29

### Added

- Add initial app version.

[Unreleased]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.4.2...HEAD
[0.4.2]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.4.1...v0.4.2
[0.4.1]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.4.0...v0.4.1
[0.4.0]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.3.0...v0.4.0
[0.3.0]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.2.1...v0.3.0
[0.2.1]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.2.0...v0.2.1
[0.2.0]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.1.1...v0.2.0
[0.1.1]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/giantswarm/macropower-analytics-panel-server-app/releases/tag/v0.1.0
