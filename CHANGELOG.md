<!--
SPDX-FileCopyrightText: Contributors to the Cable Thermal Model project

SPDX-License-Identifier: MPL-2.0
-->

# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.16.0](https://github.com/nidhi-sharma-alliander/cable-thermal-model/compare/v1.15.2...v1.16.0) (2026-07-03)


### Features

* added info to pyproject and created initial CHANGELOG ([#25](https://github.com/nidhi-sharma-alliander/cable-thermal-model/issues/25)) ([93883a5](https://github.com/nidhi-sharma-alliander/cable-thermal-model/commit/93883a5c47bf6815780893084b983a8e7de5b693))
* added publishing workflow ([#22](https://github.com/nidhi-sharma-alliander/cable-thermal-model/issues/22)) ([c060369](https://github.com/nidhi-sharma-alliander/cable-thermal-model/commit/c0603692b60e670294cf39a4b13271dafdbe95e2))
* **docstrings:** Patched some small docstring issues ([#28](https://github.com/nidhi-sharma-alliander/cable-thermal-model/issues/28)) ([d48a4fb](https://github.com/nidhi-sharma-alliander/cable-thermal-model/commit/d48a4fb72aabbbd5063e5004eec541650d83aa63))
* initial commit ([763ecd4](https://github.com/nidhi-sharma-alliander/cable-thermal-model/commit/763ecd42e49ef2162fcc82476bb0bcbb0d380d34))
* update AbstractModel and related classes to use TypeVar for static_env. ([#39](https://github.com/nidhi-sharma-alliander/cable-thermal-model/issues/39)) ([4ac26ba](https://github.com/nidhi-sharma-alliander/cable-thermal-model/commit/4ac26bafa753d5bc6e84f678d3f084c66e6dfb48))


### Bug Fixes

* various fixes to documentation ([#29](https://github.com/nidhi-sharma-alliander/cable-thermal-model/issues/29)) ([73cbdc6](https://github.com/nidhi-sharma-alliander/cable-thermal-model/commit/73cbdc60922ce98ddd8f84d6ce51432f53155951))


### Documentation

* add heat equation docs ([#35](https://github.com/nidhi-sharma-alliander/cable-thermal-model/issues/35)) ([1c31224](https://github.com/nidhi-sharma-alliander/cable-thermal-model/commit/1c31224767c91fda3115895c5cf7e9dc024919cb))
* add stateful documentation ([#23](https://github.com/nidhi-sharma-alliander/cable-thermal-model/issues/23)) ([59755dc](https://github.com/nidhi-sharma-alliander/cable-thermal-model/commit/59755dc0d7b200d7fe8bc7b63a76334b2a2cd82b))

## [1.15.2] - 2026-06-23

### Added

- First release of the cable-thermal-model package.
- Dynamic cable temperature model (DKM) for computing cable temperatures with iterative heat equation approximation.
- Support for common cable types, multiple cable circuits, different soil layers, and pipes.
- Pydantic-based schemas for cable specifications and environmental inputs.
- Comprehensive documentation and examples.
- SPDX license headers and MPL-2.0 licensing.

### Features

- `CircuitType`, `BondingType`, `CircuitYReference`, `CableLayer`, `PipeFillType`, `CablePosition` enums
- `PipeInputSchema`, `StaticEnvSoil`, `StaticEnvAir` configuration classes
- `ModelFactory` for creating cable temperature models
- `CableKey` for cable identification
- `StateSoil`, `StateAir` state tracking classes
- Full test coverage with pytest
- Pre-commit hooks and linting with ruff and mypy
- Poetry-based dependency management

[1.15.2]: https://github.com/alliander-opensource/cable-thermal-model/releases/tag/v1.15.2
