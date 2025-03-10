# Changelog

## [v1.0.0](https://github.com/fabriziosestito/rhai_rustler/tree/v1.0.0) (2023-05-20)

Breaking changes: `Rhai.eval/2` has been removed. Use `Rhai.Engine.eval/2` and `Rhai.Engine.eval_with_scope/3` instead.

[Full Changelog](https://github.com/fabriziosestito/rhai_rustler/compare/v0.1.4...v1.0.0)

- Rename/refactor Scope functions to be more ergonomic/idiomatic in Elixir [\#41](https://github.com/fabriziosestito/rhai_rustler/issues/41)
- Proper error handling [\#30](https://github.com/fabriziosestito/rhai_rustler/issues/30)
- Engine options bindings pt1 [\#36](https://github.com/fabriziosestito/rhai_rustler/pull/36) ([dottorblaster](https://github.com/dottorblaster))

- Specs are wrong [\#66](https://github.com/fabriziosestito/rhai_rustler/issues/66)

- Test file moduleresolver [\#80](https://github.com/fabriziosestito/rhai_rustler/issues/80)
- Clean-up [\#55](https://github.com/fabriziosestito/rhai_rustler/issues/55)
- Test Scope set_alias [\#53](https://github.com/fabriziosestito/rhai_rustler/issues/53)
- Add dylib example [\#43](https://github.com/fabriziosestito/rhai_rustler/issues/43)
- AST bindings [\#34](https://github.com/fabriziosestito/rhai_rustler/issues/34)
- Scope bindings [\#33](https://github.com/fabriziosestito/rhai_rustler/issues/33)
- Engine bindings [\#32](https://github.com/fabriziosestito/rhai_rustler/issues/32)

- Bump rhai to v1.14.0 and rhai_dylib to v0.1.8 [\#100](https://github.com/fabriziosestito/rhai_rustler/pull/100) ([fabriziosestito](https://github.com/fabriziosestito))
- Add test dylib module to dependabot [\#97](https://github.com/fabriziosestito/rhai_rustler/pull/97) ([fabriziosestito](https://github.com/fabriziosestito))
- Bump rustler from 0.27.0 to 0.28.0 [\#95](https://github.com/fabriziosestito/rhai_rustler/pull/95) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump rustler from 0.27.0 to 0.28.0 in /native/rhai_rustler [\#94](https://github.com/fabriziosestito/rhai_rustler/pull/94) ([dependabot[bot]](https://github.com/apps/dependabot))
- Test FileModuleResolver [\#93](https://github.com/fabriziosestito/rhai_rustler/pull/93) ([fabriziosestito](https://github.com/fabriziosestito))
- Refactor/rename Scope functions [\#92](https://github.com/fabriziosestito/rhai_rustler/pull/92) ([fabriziosestito](https://github.com/fabriziosestito))
- Add register package [\#91](https://github.com/fabriziosestito/rhai_rustler/pull/91) ([fabriziosestito](https://github.com/fabriziosestito))
- Refactor module resolvers and tests [\#90](https://github.com/fabriziosestito/rhai_rustler/pull/90) ([fabriziosestito](https://github.com/fabriziosestito))
- Remove Scope set_alias [\#88](https://github.com/fabriziosestito/rhai_rustler/pull/88) ([fabriziosestito](https://github.com/fabriziosestito))
- Bump rhai_dylib to 0.1.7 [\#87](https://github.com/fabriziosestito/rhai_rustler/pull/87) ([fabriziosestito](https://github.com/fabriziosestito))
- Bind Engine enusre_data_size_within_limits [\#86](https://github.com/fabriziosestito/rhai_rustler/pull/86) ([fabriziosestito](https://github.com/fabriziosestito))
- Use from_array [\#85](https://github.com/fabriziosestito/rhai_rustler/pull/85) ([fabriziosestito](https://github.com/fabriziosestito))
- Bind Engine register_custom_operator [\#84](https://github.com/fabriziosestito/rhai_rustler/pull/84) ([fabriziosestito](https://github.com/fabriziosestito))
- Bind Engine.disable_symbol/2 [\#83](https://github.com/fabriziosestito/rhai_rustler/pull/83) ([fabriziosestito](https://github.com/fabriziosestito))
- Bind Engine AST optimization methods [\#82](https://github.com/fabriziosestito/rhai_rustler/pull/82) ([fabriziosestito](https://github.com/fabriziosestito))
- Bind Engine::new_raw\(\) [\#81](https://github.com/fabriziosestito/rhai_rustler/pull/81) ([fabriziosestito](https://github.com/fabriziosestito))
- Bind Engine::eval\* methods [\#79](https://github.com/fabriziosestito/rhai_rustler/pull/79) ([fabriziosestito](https://github.com/fabriziosestito))
- Bind Engine::run\* methods [\#78](https://github.com/fabriziosestito/rhai_rustler/pull/78) ([fabriziosestito](https://github.com/fabriziosestito))
- Bind Engine::compile\* methods [\#77](https://github.com/fabriziosestito/rhai_rustler/pull/77) ([fabriziosestito](https://github.com/fabriziosestito))
- Bind Engine::compact_script [\#76](https://github.com/fabriziosestito/rhai_rustler/pull/76) ([fabriziosestito](https://github.com/fabriziosestito))
- Bind Engine::call_fn [\#75](https://github.com/fabriziosestito/rhai_rustler/pull/75) ([fabriziosestito](https://github.com/fabriziosestito))
- Bind AST functions and statements methods [\#74](https://github.com/fabriziosestito/rhai_rustler/pull/74) ([fabriziosestito](https://github.com/fabriziosestito))
- Bump ex_doc from 0.29.3 to 0.29.4 [\#72](https://github.com/fabriziosestito/rhai_rustler/pull/72) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bind AST::clear_functions [\#71](https://github.com/fabriziosestito/rhai_rustler/pull/71) ([fabriziosestito](https://github.com/fabriziosestito))
- Bind AST source-related methods [\#69](https://github.com/fabriziosestito/rhai_rustler/pull/69) ([fabriziosestito](https://github.com/fabriziosestito))
- macOS extension workaround [\#68](https://github.com/fabriziosestito/rhai_rustler/pull/68) ([fabriziosestito](https://github.com/fabriziosestito))
- Fix allow loop expressions test [\#67](https://github.com/fabriziosestito/rhai_rustler/pull/67) ([fabriziosestito](https://github.com/fabriziosestito))
- Bump rhai from 1.12.0 to 1.13.0 in /native/rhai_rustler [\#60](https://github.com/fabriziosestito/rhai_rustler/pull/60) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ex_doc from 0.29.2 to 0.29.3 [\#59](https://github.com/fabriziosestito/rhai_rustler/pull/59) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump thiserror from 1.0.38 to 1.0.39 in /native/rhai_rustler [\#58](https://github.com/fabriziosestito/rhai_rustler/pull/58) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ex_doc from 0.29.1 to 0.29.2 [\#57](https://github.com/fabriziosestito/rhai_rustler/pull/57) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bind Engine::run and Engine::run_with_scope [\#56](https://github.com/fabriziosestito/rhai_rustler/pull/56) ([fabriziosestito](https://github.com/fabriziosestito))
- Bind Scope::set_or_push [\#54](https://github.com/fabriziosestito/rhai_rustler/pull/54) ([fabriziosestito](https://github.com/fabriziosestito))
- Bind Scope::set_alias [\#52](https://github.com/fabriziosestito/rhai_rustler/pull/52) ([fabriziosestito](https://github.com/fabriziosestito))
- Bind Scope::pop and Scope::set_value [\#51](https://github.com/fabriziosestito/rhai_rustler/pull/51) ([fabriziosestito](https://github.com/fabriziosestito))
- Bind Scope::rewind [\#49](https://github.com/fabriziosestito/rhai_rustler/pull/49) ([fabriziosestito](https://github.com/fabriziosestito))
- Bind Scope::remove [\#47](https://github.com/fabriziosestito/rhai_rustler/pull/47) ([fabriziosestito](https://github.com/fabriziosestito))
- Bind Scope::with_capacity [\#46](https://github.com/fabriziosestito/rhai_rustler/pull/46) ([fabriziosestito](https://github.com/fabriziosestito))
- Bind Scope::len [\#45](https://github.com/fabriziosestito/rhai_rustler/pull/45) ([fabriziosestito](https://github.com/fabriziosestito))
- Bind Scope::is_empty [\#44](https://github.com/fabriziosestito/rhai_rustler/pull/44) ([fabriziosestito](https://github.com/fabriziosestito))
- Bind Scope::clone_visible [\#42](https://github.com/fabriziosestito/rhai_rustler/pull/42) ([fabriziosestito](https://github.com/fabriziosestito))
- Bind get_value instead of get [\#40](https://github.com/fabriziosestito/rhai_rustler/pull/40) ([fabriziosestito](https://github.com/fabriziosestito))
- Add scope clear [\#39](https://github.com/fabriziosestito/rhai_rustler/pull/39) ([fabriziosestito](https://github.com/fabriziosestito))
- Add credo template [\#38](https://github.com/fabriziosestito/rhai_rustler/pull/38) ([fabriziosestito](https://github.com/fabriziosestito))
- Bump rustler_precompiled from 0.6.0 to 0.6.1 [\#37](https://github.com/fabriziosestito/rhai_rustler/pull/37) ([dependabot[bot]](https://github.com/apps/dependabot))
- Add scope bindings pt 1 [\#35](https://github.com/fabriziosestito/rhai_rustler/pull/35) ([fabriziosestito](https://github.com/fabriziosestito))
- Refactor error handling [\#31](https://github.com/fabriziosestito/rhai_rustler/pull/31) ([fabriziosestito](https://github.com/fabriziosestito))
- Try to wrap Engine compile function [\#29](https://github.com/fabriziosestito/rhai_rustler/pull/29) ([dottorblaster](https://github.com/dottorblaster))
- Wrap engine pt1 [\#28](https://github.com/fabriziosestito/rhai_rustler/pull/28) ([fabriziosestito](https://github.com/fabriziosestito))
- Bump rustler_precompiled from 0.5.5 to 0.6.0 [\#26](https://github.com/fabriziosestito/rhai_rustler/pull/26) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump giantswarm/install-binary-action from 1.0.0 to 1.1.0 [\#25](https://github.com/fabriziosestito/rhai_rustler/pull/25) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump rustler from 0.26.0 to 0.27.0 in /native/rhai_rustler [\#24](https://github.com/fabriziosestito/rhai_rustler/pull/24) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump rustler from 0.26.0 to 0.27.0 [\#23](https://github.com/fabriziosestito/rhai_rustler/pull/23) ([dependabot[bot]](https://github.com/apps/dependabot))

## [v0.1.4](https://github.com/fabriziosestito/rhai_rustler/tree/v0.1.4) (2023-01-16)

[Full Changelog](https://github.com/fabriziosestito/rhai_rustler/compare/v0.1.3...v0.1.4)

- Use config to set force build [\#22](https://github.com/fabriziosestito/rhai_rustler/pull/22) ([fabriziosestito](https://github.com/fabriziosestito))
- Pin ubuntu version in release workflow [\#21](https://github.com/fabriziosestito/rhai_rustler/pull/21) ([fabriziosestito](https://github.com/fabriziosestito))

## [v0.1.3](https://github.com/fabriziosestito/rhai_rustler/tree/v0.1.3) (2023-01-03)

[Full Changelog](https://github.com/fabriziosestito/rhai_rustler/compare/v0.1.1...v0.1.3)

- Bump to v0.1.3 [\#19](https://github.com/fabriziosestito/rhai_rustler/pull/19) ([fabriziosestito](https://github.com/fabriziosestito))
- Bump rustler_precompiled from 0.5.4 to 0.5.5 [\#12](https://github.com/fabriziosestito/rhai_rustler/pull/12) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump ex_doc from 0.29.0 to 0.29.1 [\#11](https://github.com/fabriziosestito/rhai_rustler/pull/11) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump rhai from 1.10.1 to 1.11.0 in /native/rhai_rustler [\#10](https://github.com/fabriziosestito/rhai_rustler/pull/10) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump rustler_precompiled from 0.5.3 to 0.5.4 [\#9](https://github.com/fabriziosestito/rhai_rustler/pull/9) ([dependabot[bot]](https://github.com/apps/dependabot))

## [v0.1.1](https://github.com/fabriziosestito/rhai_rustler/tree/v0.1.1) (2022-11-07)

[Full Changelog](https://github.com/fabriziosestito/rhai_rustler/compare/v0.1.0...v0.1.1)

- Set fail on invalid map property [\#8](https://github.com/fabriziosestito/rhai_rustler/pull/8) ([fabriziosestito](https://github.com/fabriziosestito))

## [v0.1.0](https://github.com/fabriziosestito/rhai_rustler/tree/v0.1.0) (2022-11-04)

[Full Changelog](https://github.com/fabriziosestito/rhai_rustler/compare/7145150a1b8252fce8e3dd521d5107836a8e5132...v0.1.0)

- Add filter example [\#7](https://github.com/fabriziosestito/rhai_rustler/pull/7) ([fabriziosestito](https://github.com/fabriziosestito))
- Cleanup + README [\#6](https://github.com/fabriziosestito/rhai_rustler/pull/6) ([fabriziosestito](https://github.com/fabriziosestito))

\* _This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)_
