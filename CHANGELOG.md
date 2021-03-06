# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="1.6.0"></a>
# [1.6.0](https://github.com/appcelerator/atom-appcelerator-titanium/compare/v1.5.1...v1.6.0) (2019-03-28)


### Bug Fixes

* **autocomplete:** correct filtering of colors ([ffb340e](https://github.com/appcelerator/atom-appcelerator-titanium/commit/ffb340e)), closes [#139](https://github.com/appcelerator/atom-appcelerator-titanium/issues/139)
* **definitions:** do not suggest app.tss when generating tss for id ([1fbf454](https://github.com/appcelerator/atom-appcelerator-titanium/commit/1fbf454)), closes [#141](https://github.com/appcelerator/atom-appcelerator-titanium/issues/141)
* **toolbar:** add titles to fields ([#135](https://github.com/appcelerator/atom-appcelerator-titanium/issues/135)) ([4514d57](https://github.com/appcelerator/atom-appcelerator-titanium/commit/4514d57))
* **toolbar/android:** handle emulators being undefined, improve ui when no emulators ([f439e71](https://github.com/appcelerator/atom-appcelerator-titanium/commit/f439e71)), closes [#142](https://github.com/appcelerator/atom-appcelerator-titanium/issues/142)


### Features

* **toolbar:** add button and command to toggle toolbar visibility ([b871811](https://github.com/appcelerator/atom-appcelerator-titanium/commit/b871811)), closes [#138](https://github.com/appcelerator/atom-appcelerator-titanium/issues/138)



<a name="1.5.1"></a>
## [1.5.1](https://github.com/appcelerator/atom-appcelerator-titanium/compare/v1.5.0...v1.5.1) (2019-01-02)


### Bug Fixes

* **commands/login:** fix detection of output ([57370bf](https://github.com/appcelerator/atom-appcelerator-titanium/commit/57370bf))



<a name="1.5.0"></a>
# [1.5.0](https://github.com/appcelerator/atom-appcelerator-titanium/compare/v1.4.2...v1.5.0) (2018-12-19)


### Bug Fixes

* check for existence of type before trying to access properties ([ad4ebd2](https://github.com/appcelerator/atom-appcelerator-titanium/commit/ad4ebd2)), closes [#126](https://github.com/appcelerator/atom-appcelerator-titanium/issues/126)


### Features

* add login dialog ([a3f9601](https://github.com/appcelerator/atom-appcelerator-titanium/commit/a3f9601))


## 1.4.2

**26/10/18**

- Fixed error being thrown when tiapp.xml was saved in an invalid format (([#128]https://github.com/appcelerator/atom-appcelerator-titanium/issues/128))

## 1.4.1

**25/09/18**

- Fixed autocomplete issue when autocompleting the sdk-version tag in tiapp ([#119](https://github.com/appcelerator/atom-appcelerator-titanium/issues/119))
- Internal: Add GitHub issue templates ([#123](https://github.com/appcelerator/atom-appcelerator-titanium/pull/123))

## 1.4.0

**13/07/18**

- Added support for taking screenshots from the IDE ([#112](https://github.com/appcelerator/atom-appcelerator-titanium/pull/112), thanks to [@m1ga](https://github.com/m1ga))
- Internal: Added Travis CI to all pull requests ([#113](https://github.com/appcelerator/atom-appcelerator-titanium/pull/113))

## 1.3.0

**06/07/18**

- Added LiveView support  ([#108](https://github.com/appcelerator/atom-appcelerator-titanium/issues/108))
- Added expiration date to certificates **and** provisioning profiles ([#91](https://github.com/appcelerator/atom-appcelerator-titanium/issues/91))
- Fixed HUD-error  ([#103](https://github.com/appcelerator/atom-appcelerator-titanium/issues/103))
- Use `INFO` log-level by default, for parity with Studio  ([#90](https://github.com/appcelerator/atom-appcelerator-titanium/issues/90))
- Allow custom args to be saved across Atom sessions ([#114](https://github.com/appcelerator/atom-appcelerator-titanium/issues/114))

## 1.2.0

**01/07/18**

- Added support for cleaning the project via the toolbar ([#93](https://github.com/appcelerator/atom-appcelerator-titanium/pull/93), thanks to [@m1ga](https://github.com/m1ga))

## 1.1.1

**22/03/18**

- Default to latest SDK if none selected ([ATOM-66](https://jira.appcelerator.org/browse/ATOM-66))
- Improved Alloy create function snippets
- Fixed Slider tag autocomplete suggestion ([ATOM-70](https://jira.appcelerator.org/browse/ATOM-70))
- Fixed duplicate class suggestions and ignore blank values ([ATOM-67](https://jira.appcelerator.org/browse/ATOM-67))
- Fixed exception thrown when triggering class and ID autosuggestion ([ATOM-74](https://jira.appcelerator.org/browse/ATOM-74))

## 1.1.0

**14/02/18**

- Added support for creating new Titanium projects ([ATOM-37](https://jira.appcelerator.org/browse/ATOM-37))
- Added support for native module projects ([ATOM-38](https://jira.appcelerator.org/browse/ATOM-38))
- Added snippets support ([ATOM-11](https://jira.appcelerator.org/browse/ATOM-11))
- Added keyboard shortcuts for opening related Alloy files ([ATOM-39](https://jira.appcelerator.org/browse/ATOM-39))
- Added option to set full path to `appc` command ([ATOM-50](https://jira.appcelerator.org/browse/ATOM-50))
- Improved behaviour when non-Titanium project is open ([ATOM-40](https://jira.appcelerator.org/browse/ATOM-40))
- Improved tiapp.xml parsing ([ATOM-49](https://jira.appcelerator.org/browse/ATOM-49))
- Fixed triggering image autocompletion ([ATOM-43](https://jira.appcelerator.org/browse/ATOM-43))

## 1.0.3

**21/12/17**

- Fixed error on Linux - thanks @m1ga ([ATOM-34](https://jira.appcelerator.org/browse/ATOM-34))
- Fixed deprecation warnings ([ATOM-35](https://jira.appcelerator.org/browse/ATOM-35))
- Improve behaviour when Titanium project is not open ([ATOM-36](https://jira.appcelerator.org/browse/ATOM-35))

## 1.0.2

**09/12/17**

- Fixed issues with non-Titanium projects ([ATOM-33](https://jira.appcelerator.org/browse/ATOM-33))

## 1.0.1

**08/12/17**

- Fixed non-wildcard iOS provisioning profiles always being invalid ([ATOM-30](https://jira.appcelerator.org/browse/ATOM-30))
- Marking managed provisioning profiles as invalid ([ATOM-31](https://jira.appcelerator.org/browse/ATOM-31))
- Fixed provisioning profile ordering ([ATOM-32](https://jira.appcelerator.org/browse/ATOM-32))
- Fixed autocomplete error when creating styles for classes ([ATOM-28](https://jira.appcelerator.org/browse/ATOM-28))
- Updated publish option labelling
