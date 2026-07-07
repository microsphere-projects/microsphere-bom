# Release Notes

## v0.1.6

# Release Notes - Version 0.1.6

## Other Changes
- **Workflow Improvements**: Added Copilot-generated release notes step to the Maven Publish workflow. ([4cce001](https://example.com/commit/4cce001))
- **Version Management**: Bumped version to prepare for the next patch release. ([733c5a1](https://example.com/commit/733c5a1))
- **Release Adjustments**: Updated configuration to use raw revision for GitHub release creation. ([d624506](https://example.com/commit/d624506))

---

Thank you for using **microsphere-projects**! 🎉

## v0.1.7

# Release Notes - Version 0.1.7

## Build and Workflow Enhancements
- Added release-notes generation workflow using Copilot. ([259841d](https://github.com/your-repo/commit/259841d))
- Enhanced release notes generation prompt and updated model to `gpt-4o`. ([1008410](https://github.com/your-repo/commit/1008410), [f0b8e4e](https://github.com/your-repo/commit/f0b8e4e))
- Normalized quoting and fixed indentation in CI workflows. ([931ad92](https://github.com/your-repo/commit/931ad92), [1695e39](https://github.com/your-repo/commit/1695e39), [94484b4](https://github.com/your-repo/commit/94484b4))
- Simplified workflow job names for clarity. ([ec40fda](https://github.com/your-repo/commit/ec40fda), [c576e4b](https://github.com/your-repo/commit/c576e4b))
- Introduced matrix job for syncing branches. ([b994f08](https://github.com/your-repo/commit/b994f08))
- Added workflow to sync branches from upstream. ([07e0fd2](https://github.com/your-repo/commit/07e0fd2))

## Documentation
- Expanded README with project overview and additional links. ([c2f34f2](https://github.com/your-repo/commit/c2f34f2))

## Other Changes
- Minor refinements to configurations including trailing newline removals and prompt improvements. ([24d3c79](https://github.com/your-repo/commit/24d3c79), [02bed48](https://github.com/your-repo/commit/02bed48))
- Clarified inputs and added a full changelog link in prompts. ([36d64b6](https://github.com/your-repo/commit/36d64b6))

For a detailed changelog, refer [here](https://github.com/your-repo/compare/v0.1.6...v0.1.7).

## v0.1.8

# Release Notes: Version 0.1.8

## Build and Workflow Enhancements
- Improved release checks by using raw revision for validation. ([2ad3ec2](https://github.com/microsphere-projects/microsphere-bom/commit/2ad3ec2))
- Automated version bump to `0.1.8` after publishing `0.1.7`. ([870433e](https://github.com/microsphere-projects/microsphere-bom/commit/870433e))
- Integrated merging processes between `main` and `release` branches. ([147589a](https://github.com/microsphere-projects/microsphere-bom/commit/147589a), [7563dbe](https://github.com/microsphere-projects/microsphere-bom/commit/7563dbe), [6ef0cd9](https://github.com/microsphere-projects/microsphere-bom/commit/6ef0cd9), [4149000](https://github.com/microsphere-projects/microsphere-bom/commit/4149000))

## Documentations
- Updated release notes with appended changelog details. ([f3f15aa](https://github.com/microsphere-projects/microsphere-bom/commit/f3f15aa))

---

No new features, bug fixes, test improvements, or dependency updates in this version.

**Full Changelog**: https://github.com/microsphere-projects/microsphere-bom/compare/0.1.7...0.1.8
## v0.1.9

# Release Notes for v0.1.9

## Other Changes
- **Release Notes Improvements**:
  - Simplified release notes prompt wording. ([65ba236](https://github.com/microsphere-projects/microsphere-bom/commit/65ba236))
  - Refactored release notes formatting for clarity. ([feb0066](https://github.com/microsphere-projects/microsphere-bom/commit/feb0066))
  - Fixed formatting for release notes prompt and summary. ([fab24d1](https://github.com/microsphere-projects/microsphere-bom/commit/fab24d1))
  - Included changelog URL in the release notes summary. ([9acaa54](https://github.com/microsphere-projects/microsphere-bom/commit/9acaa54))

## Build and Workflow Enhancements
- Updated to use `FULL_CHANGELOG` variable in release notes generation. ([e301998](https://github.com/microsphere-projects/microsphere-bom/commit/e301998))
- Bumped version to `0.1.9` after publishing `0.1.8`. ([12e4280](https://github.com/microsphere-projects/microsphere-bom/commit/12e4280))

---

**View Full Changelog**: [Changelog](https://github.com/microsphere-projects/microsphere-bom/releases/tag/v0.1.9)

**Full Changelog**: https://github.com/microsphere-projects/microsphere-bom/compare/0.1.8...0.1.9## v0.2.0

# Release Notes - Version 0.2.0

## Build and Workflow Enhancements
- Improved formatting for release notes.  
- Switched to using raw revision for release updates.  
- Streamlined version bump process post-publishing.  

## Other Changes
- Merged `main` into `release` and vice versa to maintain branch parity.  

**Full Changelog**: https://github.com/microsphere-projects/microsphere-bom/compare/0.1.9...0.2.0## v0.2.1

# Release Notes - Version 0.2.1

## New Features
- Added Java 11+ Maven profile for Tomcat 10.1.54. ([d4fcc7b](#), [92d353a](#))
- Introduced Tomcat 9/10 profiles; set Tomcat 11 for Java 17. ([8c3f676](#))

## Dependency Updates
- Bumped `org.xerial:sqlite-jdbc` from `3.51.3.0` to `3.53.0.0`. ([8646092](#))

## Build and Workflow Enhancements
- Updated Maven wrapper to version `3.9.14`. ([ee8d01e](#))

## Other Changes
- Removed the Java 11+ Maven profile. ([46255e4](#)) 

---

**Full Changelog**: https://github.com/microsphere-projects/microsphere-bom/compare/0.2.0...0.2.1## v0.2.2

# Release Notes - v0.2.2

## Dependency Updates
- **Log4j 2**: Updated from `2.25.4` to `2.26.0`. ([#9](https://github.com/microsphere-projects/pull/9))
- **SQLite JDBC**: Updated from `3.53.0.0` to `3.53.1.0`. ([#8](https://github.com/microsphere-projects/pull/8))
- **Tomcat**: Updated from `11.0.21` to `11.0.22`. ([#7](https://github.com/microsphere-projects/pull/7))

## Build and Workflow Enhancements
- Updated Maven wrapper to `3.9.15`. ([1586d8e](https://github.com/microsphere-projects/commit/1586d8e))
- Switched to using the official Maven Central distribution URL for dependencies. ([a779f8d](https://github.com/microsphere-projects/commit/a779f8d))

---

For more details, please refer to the [full changelog](https://github.com/microsphere-projects/compare/0.2.1...0.2.2).

**Full Changelog**: https://github.com/microsphere-projects/microsphere-bom/compare/0.2.1...0.2.2## v0.2.3

# Release Notes: Version 0.2.3

## Dependency Updates
- **JUnit BOM**: Upgraded from `6.0.3` to `6.1.0`. ([#11](https://github.com/microsphere-projects/pull/11))
- **SLF4J API**: Upgraded from `2.0.17` to `2.0.18`. ([#10](https://github.com/microsphere-projects/pull/10))

## Build and Workflow Enhancements
- Configured Maven publishing with server credentials. ([aa9c1b4](https://github.com/microsphere-projects/commit/aa9c1b4))
- Improved Maven workflows and branch synchronization logic. ([b334c25](https://github.com/microsphere-projects/commit/b334c25))

---

No new features, bug fixes, or documentation updates were introduced in this release.

**Full Changelog**: https://github.com/microsphere-projects/microsphere-bom/compare/0.2.2...0.2.3## v0.2.4

# Release Notes - Version 0.2.4

## New Features
- **BOM Dependency Management**:  
  - Generate dependency tables for the BOM and write them to the wiki with the release version. ([#12](https://github.com/microsphere-projects/copilot/pull/12))  
  - Introduced `list-bom-dependencies` workflow action for improved automation.

## Bug Fixes
- Gracefully handle missing wiki repository scenarios.  
- Enhanced robustness for POM parsing errors with improved local fallback handling.

## Dependency Updates
- **JUnit Jupiter**: Updated to version `5.14.4`.

## Build and Workflow Enhancements
- Merged main into release branch and vice versa to maintain clean syncing.  

---

Thank you for using our project! 🚀

**Full Changelog**: https://github.com/microsphere-projects/microsphere-bom/compare/0.2.3...0.2.4## v0.2.5

# Release Notes - Version 0.2.5

## New Features
- Added `CLAUDE.md` with repository build and usage guide. (#52869fe)
- Added `USER_GUIDE.md` for Microsphere BOM. (#23225da)

## Documentation
- Enhanced repository documentation with new guides: `CLAUDE.md` and `USER_GUIDE.md`.

## Dependency Updates
- Bumped `logback.version` from 1.5.32 to 1.5.33. (#244258f)

## Build and Workflow Enhancements
- Updated parent POM to version 0.3.0. (#942e479)

---

For a detailed list of changes, refer to the full changelog in the repository. 

**Full Changelog**: https://github.com/microsphere-projects/microsphere-bom/compare/0.2.4...0.2.5## v0.2.6

# Release Notes - Version 0.2.6

## Dependency Updates
- **logback.version**: Upgraded from `1.5.33` to `1.5.34`. ([#14](https://github.com/microsphere-projects/pull/14))
- **org.xerial:sqlite-jdbc**: Upgraded from `3.53.1.0` to `3.53.2.0`. ([#15](https://github.com/microsphere-projects/pull/15))

## Build and Workflow Enhancements
- Updated parent `pom` version to `0.3.1`. 
- General maintenance: merged `main` branch into `release` and bumped patch version post-release.

**Full Changelog**: https://github.com/microsphere-projects/microsphere-bom/compare/0.2.5...0.2.6## v0.2.7

# Release Notes for Version 0.2.7

## Build and Workflow Enhancements
- **Merge Updates**: Merged `main` into `release` and `release` into `main` to sync branches. [#6698b7f, #4a9297b]

## Dependency Updates
- **Pom Update**: Modified `pom.xml` to include improvements. [#0788e74]

## Other Changes
- **Version Bump**: Incremented version to the next patch post publishing 0.2.6. [#1e9fe9a] 

---

Thank you for using our project! 🚀

**Full Changelog**: https://github.com/microsphere-projects/microsphere-bom/compare/0.2.6...0.2.7## v0.2.8

# Release Notes - Version 0.2.8

## New Features
- Added `ExampleService` for improved demonstration of functionality.  
- Simplified example POM structure for better maintainability.

## Documentation
- Added Codecov badge to `README` for enhanced visibility of test coverage.

## Dependency Updates
- Updated `microsphere-build` parent to version `0.3.4` for the latest build enhancements.

## Build and Workflow Enhancements
- Renamed example package and converted it to a Bill of Materials (BOM) setup for consistent dependency management.  
- Updated CI workflows to reflect new improvements in examples.

---

**Full Changelog**: https://github.com/microsphere-projects/microsphere-bom/compare/0.2.7...0.2.8## v0.2.9

# Release Notes for Version 0.2.9

## Dependency Updates
- Bumped `commons-logging:commons-logging` from `1.3.6` to `1.4.0`. ([#16](https://github.com/microsphere-projects/your-repo-link/pull/16))

## Build and Workflow Enhancements
- Merged release branch back into `main`. ([6041d27](https://github.com/microsphere-projects/your-repo-link/commit/6041d27), [2d34dca](https://github.com/microsphere-projects/your-repo-link/commit/2d34dca))
- Updated version to the next patch after publishing `0.2.8`. ([5b51c5f](https://github.com/microsphere-projects/your-repo-link/commit/5b51c5f))

---

**Full Changelog**: https://github.com/microsphere-projects/microsphere-bom/compare/0.2.8...0.2.9## v0.3.0

# Release Notes - Version 0.3.0

## Dependency Updates
- **Tomcat:** Bumped `tomcat.version` from `11.0.22` to `11.0.23` (#17, 4def6d9).  
- **JUnit-BOM:** Upgraded `org.junit:junit-bom` from `6.1.0` to `6.1.1` (#20, 1e18b67).  
- **Logback:** Updated `logback.version` from `1.5.34` to `1.5.37` (#21, decd280).

## Build and Workflow Enhancements
- **Microsphere Build:** Updated `microsphere-build` to version `0.3.5` (37da804).  
- Merged main branch changes into the release workflow (34ec9e3, a3263c6, 14f98b2, 46459a7).  

---

**Full Changelog**: https://github.com/microsphere-projects/microsphere-bom/compare/0.2.9...0.3.0## v0.3.2

# Release Notes for Version 0.3.2

## Dependency Updates
- **Log4j2**: Bumped `log4j2.version` from `2.26.0` to `2.26.1`. ([#22](https://github.com/microsphere-projects/microsphere/issues/22))
- **microsphere-build**: Updated parent to version `0.3.6`.

## Build and Workflow Enhancements
- Merged `main` into `release` for alignment. [skip ci]
- Merged `release` into `main` for synchronization. [skip ci] 

---

**Full Changelog**: https://github.com/microsphere-projects/microsphere-bom/compare/0.3.1...0.3.2