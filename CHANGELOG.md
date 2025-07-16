# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## v0.7.0


### 🚀 Enhancements

- Generate breaking changes section ([cc0b427](https://github.com/HoshinoSuzumi/changelogen/commit/cc0b427))
- Add missing commitlint types ([#6](https://github.com/HoshinoSuzumi/changelogen/pull/6))
- GetGitDiff ignores from ([#17](https://github.com/HoshinoSuzumi/changelogen/pull/17))
- Add gitmoji support ([#22](https://github.com/HoshinoSuzumi/changelogen/pull/22))
- Auto-update changelog files ([#24](https://github.com/HoshinoSuzumi/changelogen/pull/24))
- Support `--bump` to update version while generating changelog ([9bf9aff](https://github.com/HoshinoSuzumi/changelogen/commit/9bf9aff))
- Basic `--release` support ([934c487](https://github.com/HoshinoSuzumi/changelogen/commit/934c487))
- Generate markdown links when github is provided ([ffe1d08](https://github.com/HoshinoSuzumi/changelogen/commit/ffe1d08))
- **cli:** ⚠️  Show changelog in CLI unless bumping or releasing ([d348943](https://github.com/HoshinoSuzumi/changelogen/commit/d348943))
- Handle new version before generating changelog ([fd56f6b](https://github.com/HoshinoSuzumi/changelogen/commit/fd56f6b))
- Expose `determineSemverChange` and `bumpVersion` ([5451f18](https://github.com/HoshinoSuzumi/changelogen/commit/5451f18))
- Infer github config from package.json ([#37](https://github.com/HoshinoSuzumi/changelogen/pull/37))
- ⚠️  Resolve github usernames using `ungh/ungh` ([#46](https://github.com/HoshinoSuzumi/changelogen/pull/46))
- Update execa to v7 ([e61e2f6](https://github.com/HoshinoSuzumi/changelogen/commit/e61e2f6))
- ⚠️  Support different repository providers ([#55](https://github.com/HoshinoSuzumi/changelogen/pull/55))
- Github release integration ([#67](https://github.com/HoshinoSuzumi/changelogen/pull/67))
- Support explicit bumping as major, minor, or patch via cli ([c8afa86](https://github.com/HoshinoSuzumi/changelogen/commit/c8afa86))
- Automatically resolve github token from gh cli ([231a3ec](https://github.com/HoshinoSuzumi/changelogen/commit/231a3ec))
- Default `gh release` to latest version ([44788f5](https://github.com/HoshinoSuzumi/changelogen/commit/44788f5))
- Resolve repository config from git remote ([8401f91](https://github.com/HoshinoSuzumi/changelogen/commit/8401f91))
- Load config from `changelog` field in `package.json` ([#88](https://github.com/HoshinoSuzumi/changelogen/pull/88))
- Bump pre version ([#70](https://github.com/HoshinoSuzumi/changelogen/pull/70))
- Support templates for commit and tag messages ([#68](https://github.com/HoshinoSuzumi/changelogen/pull/68))
- Support `--publish` and `--canary` ([#123](https://github.com/HoshinoSuzumi/changelogen/pull/123))
- `repo` option as string ([#128](https://github.com/HoshinoSuzumi/changelogen/pull/128))
- Add param to require clean working dir ([#92](https://github.com/HoshinoSuzumi/changelogen/pull/92), [#93](https://github.com/HoshinoSuzumi/changelogen/pull/93))
- Add excludeAuthors option ([#95](https://github.com/HoshinoSuzumi/changelogen/pull/95))
- Add option to sign git tags ([#117](https://github.com/HoshinoSuzumi/changelogen/pull/117))
- **git:** Support parse git messages that have prefix emoji ([#146](https://github.com/HoshinoSuzumi/changelogen/pull/146))
- Update jiti to v2 ([6e85d32](https://github.com/HoshinoSuzumi/changelogen/commit/6e85d32))
- Add check for breaking changes in commit body ([#228](https://github.com/HoshinoSuzumi/changelogen/pull/228))
- Hide author email address via flag ([#247](https://github.com/HoshinoSuzumi/changelogen/pull/247))
- Add `noAuthors` option ([#183](https://github.com/HoshinoSuzumi/changelogen/pull/183))
- **cli:** Add options to include/exclude merge commits in changelog ([c32cd00](https://github.com/HoshinoSuzumi/changelogen/commit/c32cd00))
- **cli:** Add options to include/exclude merge commits in changelog ([a03671d](https://github.com/HoshinoSuzumi/changelogen/commit/a03671d))

### 🩹 Fixes

- Avoid `.exec` for multi matches ([7c612fc](https://github.com/HoshinoSuzumi/changelogen/commit/7c612fc))
- Format names for case matching ([ece2d90](https://github.com/HoshinoSuzumi/changelogen/commit/ece2d90))
- **cli:** Use `/usr/bin/env` ([#5](https://github.com/HoshinoSuzumi/changelogen/pull/5))
- Remove `general` in entries without scope ([31a0861](https://github.com/HoshinoSuzumi/changelogen/commit/31a0861))
- Expose `./config` ([#10](https://github.com/HoshinoSuzumi/changelogen/pull/10))
- Use `getCurrentGitRef` ([#15](https://github.com/HoshinoSuzumi/changelogen/pull/15))
- **parse:** ⚠️  `references` with type ([#27](https://github.com/HoshinoSuzumi/changelogen/pull/27))
- Convertminor to patch for 0.x versions ([011b6a1](https://github.com/HoshinoSuzumi/changelogen/commit/011b6a1))
- Run release step last ([b052f55](https://github.com/HoshinoSuzumi/changelogen/commit/b052f55))
- Handle breaking change commits for bumping ([f7ffaa4](https://github.com/HoshinoSuzumi/changelogen/commit/f7ffaa4))
- Show original semver type without 0.x changes in log ([ddd818a](https://github.com/HoshinoSuzumi/changelogen/commit/ddd818a))
- Use `v` prefix for git tag and annotate ([bf6b5da](https://github.com/HoshinoSuzumi/changelogen/commit/bf6b5da))
- Add missing annotate message ([157b0c5](https://github.com/HoshinoSuzumi/changelogen/commit/157b0c5))
- Use last commit for changelog diff ([6ac4b4b](https://github.com/HoshinoSuzumi/changelogen/commit/6ac4b4b))
- Use h2 for title ([fc0967c](https://github.com/HoshinoSuzumi/changelogen/commit/fc0967c))
- Import semver as default import ([3bd0b61](https://github.com/HoshinoSuzumi/changelogen/commit/3bd0b61))
- Use `creatordate` to find last tag ([#39](https://github.com/HoshinoSuzumi/changelogen/pull/39))
- Use release version in changelog title ([04671a6](https://github.com/HoshinoSuzumi/changelogen/commit/04671a6))
- Let `--output` work without value ([#43](https://github.com/HoshinoSuzumi/changelogen/pull/43))
- Consider docs and refactor as semver patch for bump ([648ccf1](https://github.com/HoshinoSuzumi/changelogen/commit/648ccf1))
- Only skip non breaking `chre(deps)` ([20e622e](https://github.com/HoshinoSuzumi/changelogen/commit/20e622e))
- **markdown:** Avoid rendering `noreply.github.com` emails ([4871721](https://github.com/HoshinoSuzumi/changelogen/commit/4871721))
- Avoid rendering authors with `[bot]` in their name ([4f3f644](https://github.com/HoshinoSuzumi/changelogen/commit/4f3f644))
- Format name to avoid duplicates ([f74a988](https://github.com/HoshinoSuzumi/changelogen/commit/f74a988))
- Bump by patch by default ([7e38438](https://github.com/HoshinoSuzumi/changelogen/commit/7e38438))
- Stage `CHANGELOG.md` and `package.json` when releasing ([69d375c](https://github.com/HoshinoSuzumi/changelogen/commit/69d375c))
- Add correct output file to git ([#64](https://github.com/HoshinoSuzumi/changelogen/pull/64))
- Update ungh link ([a5ab510](https://github.com/HoshinoSuzumi/changelogen/commit/a5ab510))
- Only access latest tag accessible from current branch ([#69](https://github.com/HoshinoSuzumi/changelogen/pull/69))
- **cli:** Don't eat up first `-*` arg ([77b483b](https://github.com/HoshinoSuzumi/changelogen/commit/77b483b))
- Allow providing no versions ([ac84c39](https://github.com/HoshinoSuzumi/changelogen/commit/ac84c39))
- Use parsed release body ([aec2341](https://github.com/HoshinoSuzumi/changelogen/commit/aec2341))
- Strip title line from release ([319f7ce](https://github.com/HoshinoSuzumi/changelogen/commit/319f7ce))
- Handle unset value for `config.repo` ([#72](https://github.com/HoshinoSuzumi/changelogen/pull/72))
- **getLastGitTag:** Handle when there are no git tags ([#77](https://github.com/HoshinoSuzumi/changelogen/pull/77))
- **markdown:** Remove unnecessary spaces ([#106](https://github.com/HoshinoSuzumi/changelogen/pull/106))
- Add missing type export to package.json ([#113](https://github.com/HoshinoSuzumi/changelogen/pull/113))
- Extra spaces in contributors and breaking changes ([#134](https://github.com/HoshinoSuzumi/changelogen/pull/134))
- Repo name with `-` or `.` ([#127](https://github.com/HoshinoSuzumi/changelogen/pull/127))
- **github:** Use bearer token ([#180](https://github.com/HoshinoSuzumi/changelogen/pull/180))
- Handle repo name with multiple segments ([#219](https://github.com/HoshinoSuzumi/changelogen/pull/219))
- Lowercase scope when filtering ([#199](https://github.com/HoshinoSuzumi/changelogen/pull/199))
- **bump:** Avoid using `+` for canary suffix ([#224](https://github.com/HoshinoSuzumi/changelogen/pull/224))
- Use `https` proto for author's github link ([#225](https://github.com/HoshinoSuzumi/changelogen/pull/225))
- Use `https` proto for author's github link in tests ([#226](https://github.com/HoshinoSuzumi/changelogen/pull/226))
- Release version regex supporting pre versions ([#259](https://github.com/HoshinoSuzumi/changelogen/pull/259))
- Use correct compare changes URL for Bitbucket ([#257](https://github.com/HoshinoSuzumi/changelogen/pull/257))
- Use tag template for version title and compare change link ([#255](https://github.com/HoshinoSuzumi/changelogen/pull/255))
- Render usernames in github changelog ([#265](https://github.com/HoshinoSuzumi/changelogen/pull/265))
- Pass `cwd` in more places before running commands ([#266](https://github.com/HoshinoSuzumi/changelogen/pull/266))
- **cli:** Accept `hideAuthorEmail` arg ([#275](https://github.com/HoshinoSuzumi/changelogen/pull/275))

### 💅 Refactors

- Update emojies ([3c4fbac](https://github.com/HoshinoSuzumi/changelogen/commit/3c4fbac))
- Update types ([6f19cb3](https://github.com/HoshinoSuzumi/changelogen/commit/6f19cb3))
- ⚠️  Use flat scopes ([8e33e93](https://github.com/HoshinoSuzumi/changelogen/commit/8e33e93))
- Use lines array for constructing markdown ([#16](https://github.com/HoshinoSuzumi/changelogen/pull/16))
- Upgrade to `open` v9 ([315cbd0](https://github.com/HoshinoSuzumi/changelogen/commit/315cbd0))
- Replace `execa` with `execSync` ([#222](https://github.com/HoshinoSuzumi/changelogen/pull/222))
- Use human readable date for canary versions ([#223](https://github.com/HoshinoSuzumi/changelogen/pull/223))
- Update execCommand ([68127be](https://github.com/HoshinoSuzumi/changelogen/commit/68127be))
- Use consola for colors ([49e0401](https://github.com/HoshinoSuzumi/changelogen/commit/49e0401))
- Use confbox for yaml parsing ([19e940c](https://github.com/HoshinoSuzumi/changelogen/commit/19e940c))

### 📖 Documentation

- Small improvement ([#4](https://github.com/HoshinoSuzumi/changelogen/pull/4))
- Use `npx changelogen@latest` to ensure using latest version ([8ec40b5](https://github.com/HoshinoSuzumi/changelogen/commit/8ec40b5))
- Fix from format ([4373a86](https://github.com/HoshinoSuzumi/changelogen/commit/4373a86))
- Add documentation about `--push` flag ([#114](https://github.com/HoshinoSuzumi/changelogen/pull/114))
- Add note about version number interpretation ([#272](https://github.com/HoshinoSuzumi/changelogen/pull/272))

### 📦 Build

- Use dynamic import for execa for cjs support ([a794cf1](https://github.com/HoshinoSuzumi/changelogen/commit/a794cf1))
- ⚠️  Esm-only dist ([4a22de6](https://github.com/HoshinoSuzumi/changelogen/commit/4a22de6))

### 🌊 Types

- `config.types` accept `boolean` value ([#278](https://github.com/HoshinoSuzumi/changelogen/pull/278))

### 🏡 Chore

- Disable starter test ([9edd62d](https://github.com/HoshinoSuzumi/changelogen/commit/9edd62d))
- **release:** 0.0.2 ([38d7ba1](https://github.com/HoshinoSuzumi/changelogen/commit/38d7ba1))
- **release:** 0.0.3 ([1c0dcb7](https://github.com/HoshinoSuzumi/changelogen/commit/1c0dcb7))
- **release:** 0.0.4 ([125fc28](https://github.com/HoshinoSuzumi/changelogen/commit/125fc28))
- **release:** 0.0.5 ([0fb47ec](https://github.com/HoshinoSuzumi/changelogen/commit/0fb47ec))
- **release:** 0.0.6 ([ce317f8](https://github.com/HoshinoSuzumi/changelogen/commit/ce317f8))
- Comment unused fn ([9735e2e](https://github.com/HoshinoSuzumi/changelogen/commit/9735e2e))
- **release:** 0.1.0 ([79d6a90](https://github.com/HoshinoSuzumi/changelogen/commit/79d6a90))
- **release:** 0.1.1 ([37c407c](https://github.com/HoshinoSuzumi/changelogen/commit/37c407c))
- Update lockfile and vitest config ([48f609b](https://github.com/HoshinoSuzumi/changelogen/commit/48f609b))
- Use changelogen release flow ([2a8bb4f](https://github.com/HoshinoSuzumi/changelogen/commit/2a8bb4f))
- **release:** 0.2.0 ([0ee9ecf](https://github.com/HoshinoSuzumi/changelogen/commit/0ee9ecf))
- **release:** 0.2.1 ([99c4e6e](https://github.com/HoshinoSuzumi/changelogen/commit/99c4e6e))
- **release:** 0.2.2 ([d0ef976](https://github.com/HoshinoSuzumi/changelogen/commit/d0ef976))
- **release:** 0.2.3 ([8487e91](https://github.com/HoshinoSuzumi/changelogen/commit/8487e91))
- **release:** 0.3.0 ([cdc7dd4](https://github.com/HoshinoSuzumi/changelogen/commit/cdc7dd4))
- **release:** V0.3.1 ([25d8acc](https://github.com/HoshinoSuzumi/changelogen/commit/25d8acc))
- **release:** V0.3.2 ([5c2babc](https://github.com/HoshinoSuzumi/changelogen/commit/5c2babc))
- Manually update old changelog entries ([c3ff561](https://github.com/HoshinoSuzumi/changelogen/commit/c3ff561))
- Update dependencies ([c210976](https://github.com/HoshinoSuzumi/changelogen/commit/c210976))
- Fix typecheck ([8796cf1](https://github.com/HoshinoSuzumi/changelogen/commit/8796cf1))
- **release:** V0.3.3 ([f4f42a3](https://github.com/HoshinoSuzumi/changelogen/commit/f4f42a3))
- **release:** V0.3.4 ([6fc5087](https://github.com/HoshinoSuzumi/changelogen/commit/6fc5087))
- **release:** V0.3.5 ([3828bda](https://github.com/HoshinoSuzumi/changelogen/commit/3828bda))
- **release:** V0.4.0 ([a3cafa9](https://github.com/HoshinoSuzumi/changelogen/commit/a3cafa9))
- Update renovate config ([#54](https://github.com/HoshinoSuzumi/changelogen/pull/54))
- Update dependencies ([4216bc6](https://github.com/HoshinoSuzumi/changelogen/commit/4216bc6))
- Update repo ([83c349f](https://github.com/HoshinoSuzumi/changelogen/commit/83c349f))
- **release:** V0.4.1 ([d126f3a](https://github.com/HoshinoSuzumi/changelogen/commit/d126f3a))
- Fix lint issue and update snapshots ([e162ab8](https://github.com/HoshinoSuzumi/changelogen/commit/e162ab8))
- Mention gh cli login ([7f4a05f](https://github.com/HoshinoSuzumi/changelogen/commit/7f4a05f))
- **release:** V0.5.0 ([585594e](https://github.com/HoshinoSuzumi/changelogen/commit/585594e))
- Simplify release command ([225fa64](https://github.com/HoshinoSuzumi/changelogen/commit/225fa64))
- **release:** V0.5.1 ([a14d749](https://github.com/HoshinoSuzumi/changelogen/commit/a14d749))
- Update badges and small improvements ([146d1d4](https://github.com/HoshinoSuzumi/changelogen/commit/146d1d4))
- Update dev dependencies ([0f44ee9](https://github.com/HoshinoSuzumi/changelogen/commit/0f44ee9))
- **release:** V0.5.2 ([0a5d6c8](https://github.com/HoshinoSuzumi/changelogen/commit/0a5d6c8))
- **release:** V0.5.3 ([db1c625](https://github.com/HoshinoSuzumi/changelogen/commit/db1c625))
- **release:** V0.5.4 ([de240e5](https://github.com/HoshinoSuzumi/changelogen/commit/de240e5))
- Update dependencies ([81f37bf](https://github.com/HoshinoSuzumi/changelogen/commit/81f37bf))
- Keep prettier compatible ([cb9adf4](https://github.com/HoshinoSuzumi/changelogen/commit/cb9adf4))
- Add autofix ci ([5bfe08e](https://github.com/HoshinoSuzumi/changelogen/commit/5bfe08e))
- **release:** V0.5.5 ([14fa199](https://github.com/HoshinoSuzumi/changelogen/commit/14fa199))
- Apply automated lint fixes ([72c407f](https://github.com/HoshinoSuzumi/changelogen/commit/72c407f))
- Update ci ([bcb16cb](https://github.com/HoshinoSuzumi/changelogen/commit/bcb16cb))
- Update non major deps ([7f714c9](https://github.com/HoshinoSuzumi/changelogen/commit/7f714c9))
- Update to eslint v9 ([fd40be9](https://github.com/HoshinoSuzumi/changelogen/commit/fd40be9))
- Apply automated lint fixes ([673255b](https://github.com/HoshinoSuzumi/changelogen/commit/673255b))
- Update deps ([3cfbe27](https://github.com/HoshinoSuzumi/changelogen/commit/3cfbe27))
- **release:** V0.5.6 ([5f263da](https://github.com/HoshinoSuzumi/changelogen/commit/5f263da))
- **release:** V0.5.7 ([c3796c4](https://github.com/HoshinoSuzumi/changelogen/commit/c3796c4))
- Lint ([031cfd6](https://github.com/HoshinoSuzumi/changelogen/commit/031cfd6))
- Update deps ([b184f23](https://github.com/HoshinoSuzumi/changelogen/commit/b184f23))
- Update ci ([8662c4e](https://github.com/HoshinoSuzumi/changelogen/commit/8662c4e))
- Update esm-only deps ([0d5e31d](https://github.com/HoshinoSuzumi/changelogen/commit/0d5e31d))
- **release:** V0.6.0 ([7c20c8d](https://github.com/HoshinoSuzumi/changelogen/commit/7c20c8d))
- Update deps ([f728b52](https://github.com/HoshinoSuzumi/changelogen/commit/f728b52))
- Update tsconfig ([e5dced7](https://github.com/HoshinoSuzumi/changelogen/commit/e5dced7))
- **release:** V0.6.1 ([17ce7c7](https://github.com/HoshinoSuzumi/changelogen/commit/17ce7c7))
- **readme:** Fix typo ([#270](https://github.com/HoshinoSuzumi/changelogen/pull/270))
- Update deps ([037ac74](https://github.com/HoshinoSuzumi/changelogen/commit/037ac74))
- **release:** V0.6.2 ([acdedaa](https://github.com/HoshinoSuzumi/changelogen/commit/acdedaa))

### ✅ Tests

- Update snapshot ([102aa98](https://github.com/HoshinoSuzumi/changelogen/commit/102aa98))
- Update snapshot ([b264c80](https://github.com/HoshinoSuzumi/changelogen/commit/b264c80))
- Add tests for parsing co-authors from commit body ([#229](https://github.com/HoshinoSuzumi/changelogen/pull/229))
- Update snapshot ([ec2618f](https://github.com/HoshinoSuzumi/changelogen/commit/ec2618f))

#### ⚠️ Breaking Changes

- **cli:** ⚠️  Show changelog in CLI unless bumping or releasing ([d348943](https://github.com/HoshinoSuzumi/changelogen/commit/d348943))
- ⚠️  Resolve github usernames using `ungh/ungh` ([#46](https://github.com/HoshinoSuzumi/changelogen/pull/46))
- ⚠️  Support different repository providers ([#55](https://github.com/HoshinoSuzumi/changelogen/pull/55))
- **parse:** ⚠️  `references` with type ([#27](https://github.com/HoshinoSuzumi/changelogen/pull/27))
- ⚠️  Use flat scopes ([8e33e93](https://github.com/HoshinoSuzumi/changelogen/commit/8e33e93))
- ⚠️  Esm-only dist ([4a22de6](https://github.com/HoshinoSuzumi/changelogen/commit/4a22de6))

### ❤️ Contributors

- Timothy Yin ([@HoshinoSuzumi](https://github.com/HoshinoSuzumi))
- Pooya Parsa ([@pi0](https://github.com/pi0))
- Philipp Kief ([@PKief](https://github.com/PKief))
- Azat S. ([@azat-io](https://github.com/azat-io))
- Adarsh DK <adarsh.dk24012@gmail.com>
- B. Jonson <www.jbc.bd@gmail.com>
- Daniel Roe ([@danielroe](https://github.com/danielroe))
- Klein Petr ([@kleinpetr](https://github.com/kleinpetr))
- Jasper Zonneveld
- Thorsten Seyschab ([@toddeTV](https://github.com/toddeTV))
- Jan-Henrik Damaschke <jdamaschke@outlook.de>
- Damian Głowala ([@DamianGlowala](https://github.com/DamianGlowala))
- Wan Chiu ([@wan54](https://github.com/wan54))
- Jianqi Pan ([@Jannchie](https://github.com/Jannchie))
- Vasily Kuzin <exer7um@gmail.com>
- John Campion Jr <john@brightshore.com>
- Waleed Khaled ([@Waleed-KH](https://github.com/Waleed-KH))
- Maciej Kasprzyk <kapustka.maciek@gmail.com>
- Mazel <me@loicmazuel.com>
- Thomas Lamant ([@tmlmt](https://github.com/tmlmt))
- Zhong666 ([@aa900031](https://github.com/aa900031))
- Donald Shtjefni ([@dnldsht](https://github.com/dnldsht))
- Sébastien Chopin <seb@nuxtjs.com>
- Nozomu Ikuta <nick.0508.nick@gmail.com>
- Lvjiaxuan <471501748@qq.com>
- Ahad Birang <farnabaz@gmail.com>
- Conner ([@Intevel](https://github.com/Intevel))
- Anthony Fu <anthonyfu117@hotmail.com>
- 三咲智子 <sxzz@sxzz.moe>
- Julien Ripouteau ([@Julien-R44](https://github.com/Julien-R44))

## v0.6.2

[compare changes](https://github.com/unjs/changelogen/compare/v0.6.1...v0.6.2)

### 🩹 Fixes

- **cli:** Accept `hideAuthorEmail` arg ([#275](https://github.com/unjs/changelogen/pull/275))

### 📖 Documentation

- Add note about version number interpretation ([#272](https://github.com/unjs/changelogen/pull/272))

### 🌊 Types

- `config.types` accept `boolean` value ([#278](https://github.com/unjs/changelogen/pull/278))

### 🏡 Chore

- **readme:** Fix typo ([#270](https://github.com/unjs/changelogen/pull/270))
- Update deps ([037ac74](https://github.com/unjs/changelogen/commit/037ac74))

### ❤️ Contributors

- Philipp Kief ([@PKief](https://github.com/PKief))
- Pooya Parsa ([@pi0](https://github.com/pi0))
- Azat S. ([@azat-io](https://github.com/azat-io))
- Adarsh DK <adarsh.dk24012@gmail.com>
- B. Jonson ([@who-jonson](https://github.com/who-jonson))

## v0.6.1

[compare changes](https://github.com/unjs/changelogen/compare/v0.6.0...v0.6.1)

### 🩹 Fixes

- Pass `cwd` in more places before running commands ([#266](https://github.com/unjs/changelogen/pull/266))

### 🏡 Chore

- Update deps ([f728b52](https://github.com/unjs/changelogen/commit/f728b52))
- Update tsconfig ([e5dced7](https://github.com/unjs/changelogen/commit/e5dced7))

### ✅ Tests

- Update snapshot ([ec2618f](https://github.com/unjs/changelogen/commit/ec2618f))

### ❤️ Contributors

- Pooya Parsa ([@pi0](https://github.com/pi0))
- Daniel Roe ([@danielroe](https://github.com/danielroe))

## v0.6.0

[compare changes](https://github.com/unjs/changelogen/compare/v0.5.7...v0.6.0)

### 🚀 Enhancements

- Update jiti to v2 ([6e85d32](https://github.com/unjs/changelogen/commit/6e85d32))
- Add check for breaking changes in commit body ([#228](https://github.com/unjs/changelogen/pull/228))
- Hide author email address via flag ([#247](https://github.com/unjs/changelogen/pull/247))
- Add `noAuthors` option ([#183](https://github.com/unjs/changelogen/pull/183))

### 🩹 Fixes

- Use `https` proto for author's github link ([#225](https://github.com/unjs/changelogen/pull/225))
- Use `https` proto for author's github link in tests ([#226](https://github.com/unjs/changelogen/pull/226))
- Release version regex supporting pre versions ([#259](https://github.com/unjs/changelogen/pull/259))
- Use correct compare changes URL for Bitbucket ([#257](https://github.com/unjs/changelogen/pull/257))
- Use tag template for version title and compare change link ([#255](https://github.com/unjs/changelogen/pull/255))
- Render usernames in github changelog ([#265](https://github.com/unjs/changelogen/pull/265))

### 💅 Refactors

- Use consola for colors ([49e0401](https://github.com/unjs/changelogen/commit/49e0401))
- Use confbox for yaml parsing ([19e940c](https://github.com/unjs/changelogen/commit/19e940c))

### 📦 Build

- ⚠️  Esm-only dist ([4a22de6](https://github.com/unjs/changelogen/commit/4a22de6))

### 🏡 Chore

- Lint ([031cfd6](https://github.com/unjs/changelogen/commit/031cfd6))
- Update deps ([b184f23](https://github.com/unjs/changelogen/commit/b184f23))
- Update ci ([8662c4e](https://github.com/unjs/changelogen/commit/8662c4e))
- Update esm-only deps ([0d5e31d](https://github.com/unjs/changelogen/commit/0d5e31d))

### ✅ Tests

- Add tests for parsing co-authors from commit body ([#229](https://github.com/unjs/changelogen/pull/229))

#### ⚠️ Breaking Changes

- ⚠️  Esm-only dist ([4a22de6](https://github.com/unjs/changelogen/commit/4a22de6))

### ❤️ Contributors

- Pooya Parsa ([@pi0](https://github.com/pi0))
- Klein Petr ([@kleinpetr](https://github.com/kleinpetr))
- Jasper Zonneveld ([@JaZo](https://github.com/JaZo))
- Thorsten Seyschab ([@toddeTV](https://github.com/toddeTV))
- Philipp Kief ([@PKief](https://github.com/PKief))
- Jan-Henrik Damaschke <jdamaschke@outlook.de>
- Damian Głowala ([@DamianGlowala](https://github.com/DamianGlowala))

## v0.5.7

[compare changes](https://github.com/unjs/changelogen/compare/v0.5.6...v0.5.7)

### 🩹 Fixes

- **bump:** Avoid using `+` for canary suffix ([#224](https://github.com/unjs/changelogen/pull/224))

### ❤️ Contributors

- Pooya Parsa ([@pi0](http://github.com/pi0))

## v0.5.6

[compare changes](https://github.com/unjs/changelogen/compare/v0.5.5...v0.5.6)

### 🚀 Enhancements

- Add option to sign git tags ([#117](https://github.com/unjs/changelogen/pull/117))
- **git:** Support parse git messages that have prefix emoji ([#146](https://github.com/unjs/changelogen/pull/146))

### 🩹 Fixes

- **github:** Use bearer token ([#180](https://github.com/unjs/changelogen/pull/180))
- Handle repo name with multiple segments ([#219](https://github.com/unjs/changelogen/pull/219))
- Lowercase scope when filtering ([#199](https://github.com/unjs/changelogen/pull/199))

### 💅 Refactors

- Replace `execa` with `execSync` ([#222](https://github.com/unjs/changelogen/pull/222))
- Use human readable date for canary versions ([#223](https://github.com/unjs/changelogen/pull/223))
- Update execCommand ([68127be](https://github.com/unjs/changelogen/commit/68127be))

### 🏡 Chore

- Apply automated lint fixes ([72c407f](https://github.com/unjs/changelogen/commit/72c407f))
- Update ci ([bcb16cb](https://github.com/unjs/changelogen/commit/bcb16cb))
- Update non major deps ([7f714c9](https://github.com/unjs/changelogen/commit/7f714c9))
- Update to eslint v9 ([fd40be9](https://github.com/unjs/changelogen/commit/fd40be9))
- Apply automated lint fixes ([673255b](https://github.com/unjs/changelogen/commit/673255b))
- Update deps ([3cfbe27](https://github.com/unjs/changelogen/commit/3cfbe27))

### ❤️ Contributors

- Pooya Parsa ([@pi0](http://github.com/pi0))
- Klein Petr ([@kleinpetr](http://github.com/kleinpetr))
- Wan Chiu ([@wan54](http://github.com/wan54))
- Jianqi Pan ([@Jannchie](http://github.com/Jannchie))
- Vasily Kuzin <exer7um@gmail.com>
- Daniel Roe ([@danielroe](http://github.com/danielroe))

## v0.5.5

[compare changes](https://github.com/unjs/changelogen/compare/v0.5.4...v0.5.5)

### 🚀 Enhancements

- `repo` option as string ([#128](https://github.com/unjs/changelogen/pull/128))
- Add param to require clean working dir ([#92](https://github.com/unjs/changelogen/pull/92), [#93](https://github.com/unjs/changelogen/pull/93))
- Add excludeAuthors option ([#95](https://github.com/unjs/changelogen/pull/95))

### 🩹 Fixes

- Extra spaces in contributors and breaking changes ([#134](https://github.com/unjs/changelogen/pull/134))
- Repo name with `-` or `.` ([#127](https://github.com/unjs/changelogen/pull/127))

### 🏡 Chore

- Update dependencies ([81f37bf](https://github.com/unjs/changelogen/commit/81f37bf))
- Keep prettier compatible ([cb9adf4](https://github.com/unjs/changelogen/commit/cb9adf4))
- Add autofix ci ([5bfe08e](https://github.com/unjs/changelogen/commit/5bfe08e))

### ❤️ Contributors

- John Campion Jr <john@brightshore.com>
- Waleed Khaled ([@Waleed-KH](http://github.com/Waleed-KH))
- Maciej Kasprzyk <kapustka.maciek@gmail.com>
- Pooya Parsa ([@pi0](http://github.com/pi0))

## v0.5.4

[compare changes](https://github.com/unjs/changelogen/compare/v0.5.3...v0.5.4)

### 🚀 Enhancements

- Support `--publish` and `--canary` ([#123](https://github.com/unjs/changelogen/pull/123))

### 🩹 Fixes

- **markdown:** Remove unnecessary spaces ([#106](https://github.com/unjs/changelogen/pull/106))
- Add missing type export to package.json ([#113](https://github.com/unjs/changelogen/pull/113))

### 📖 Documentation

- Add documentation about `--push` flag ([#114](https://github.com/unjs/changelogen/pull/114))

### ❤️  Contributors

- Daniel Roe <daniel@roe.dev>
- Mazel <me@loicmazuel.com>
- Waleed Khaled ([@Waleed-KH](http://github.com/Waleed-KH))
- Thomas Lamant ([@tmlmt](http://github.com/tmlmt))

## v0.5.3

[compare changes](https://github.com/unjs/changelogen/compare/v0.5.2...v0.5.3)

## v0.5.2

[compare changes](https://github.com/unjs/changelogen/compare/v0.5.1...v0.5.2)


### 🚀 Enhancements

  - Resolve repository config from git remote ([8401f91](https://github.com/unjs/changelogen/commit/8401f91))
  - Load config from `changelog` field in `package.json` ([#88](https://github.com/unjs/changelogen/pull/88))
  - Bump pre version ([#70](https://github.com/unjs/changelogen/pull/70))
  - Support templates for commit and tag messages ([#68](https://github.com/unjs/changelogen/pull/68))

### 🩹 Fixes

  - Handle unset value for `config.repo` ([#72](https://github.com/unjs/changelogen/pull/72))
  - **getLastGitTag:** Handle when there are no git tags ([#77](https://github.com/unjs/changelogen/pull/77))

### 💅 Refactors

  - Upgrade to `open` v9 ([315cbd0](https://github.com/unjs/changelogen/commit/315cbd0))

### 🏡 Chore

  - Update badges and small improvements ([146d1d4](https://github.com/unjs/changelogen/commit/146d1d4))
  - Update dev dependencies ([0f44ee9](https://github.com/unjs/changelogen/commit/0f44ee9))

### ❤️  Contributors

- Zhong666 ([@aa900031](http://github.com/aa900031))
- Donald Shtjefni ([@dnldsht](http://github.com/dnldsht))
- Pooya Parsa ([@pi0](http://github.com/pi0))
- Sébastien Chopin <seb@nuxtjs.com>

## v0.5.1

[compare changes](https://github.com/unjs/changelogen/compare/v0.5.0...v0.5.1)


### 🩹 Fixes

  - Allow providing no versions ([ac84c39](https://github.com/unjs/changelogen/commit/ac84c39))
  - Use parsed release body ([aec2341](https://github.com/unjs/changelogen/commit/aec2341))
  - Strip title line from release ([319f7ce](https://github.com/unjs/changelogen/commit/319f7ce))

### 🏡 Chore

  - Simplify release command ([225fa64](https://github.com/unjs/changelogen/commit/225fa64))

### ❤️  Contributors

- Pooya Parsa ([@pi0](http://github.com/pi0))

## v0.5.0

[compare changes](https://github.com/unjs/changelogen/compare/v0.4.1...v0.5.0)


### 🚀 Enhancements

  - Update execa to v7 ([e61e2f6](https://github.com/unjs/changelogen/commit/e61e2f6))
  - ⚠️  Support different repository providers ([#55](https://github.com/unjs/changelogen/pull/55))
  - Github release integration ([#67](https://github.com/unjs/changelogen/pull/67))
  - Support explicit bumping as major, minor, or patch via cli ([c8afa86](https://github.com/unjs/changelogen/commit/c8afa86))
  - Automatically resolve github token from gh cli ([231a3ec](https://github.com/unjs/changelogen/commit/231a3ec))
  - Default `gh release` to latest version ([44788f5](https://github.com/unjs/changelogen/commit/44788f5))

### 🩹 Fixes

  - Stage `CHANGELOG.md` and `package.json` when releasing ([69d375c](https://github.com/unjs/changelogen/commit/69d375c))
  - Add correct output file to git ([#64](https://github.com/unjs/changelogen/pull/64))
  - Update ungh link ([a5ab510](https://github.com/unjs/changelogen/commit/a5ab510))
  - Only access latest tag accessible from current branch ([#69](https://github.com/unjs/changelogen/pull/69))
  - **cli:** Don't eat up first `-*` arg ([77b483b](https://github.com/unjs/changelogen/commit/77b483b))

### 🏡 Chore

  - Fix lint issue and update snapshots ([e162ab8](https://github.com/unjs/changelogen/commit/e162ab8))
  - Mention gh cli login ([7f4a05f](https://github.com/unjs/changelogen/commit/7f4a05f))

#### ⚠️  Breaking Changes

  - ⚠️  Support different repository providers ([#55](https://github.com/unjs/changelogen/pull/55))

### ❤️  Contributors

- Pooya Parsa ([@pi0](http://github.com/pi0))
- Daniel Roe <daniel@roe.dev>
- Donald Shtjefni ([@dnldsht](http://github.com/dnldsht))

## v0.4.1

[compare changes](https://github.com/unjs/changelogen/compare/v0.4.0...v0.4.1)


### 🩹 Fixes

  - Bump by patch by default ([7e38438](https://github.com/unjs/changelogen/commit/7e38438))

### 🏡 Chore

  - Update renovate config ([#54](https://github.com/unjs/changelogen/pull/54))
  - Update dependencies ([4216bc6](https://github.com/unjs/changelogen/commit/4216bc6))
  - Update repo ([83c349f](https://github.com/unjs/changelogen/commit/83c349f))

### ❤️  Contributors

- Pooya Parsa <pooya@pi0.io>
- Nozomu Ikuta <nick.0508.nick@gmail.com>

## v0.4.0

[compare changes](https://github.com/unjs/changelogen/compare/v0.3.5...v0.4.0)


### 🚀 Enhancements

  - ⚠️  Resolve github usernames using `ungh/ungh` ([#46](https://github.com/unjs/changelogen/pull/46))

### 🩹 Fixes

  - **markdown:** Avoid rendering `noreply.github.com` emails ([4871721](https://github.com/unjs/changelogen/commit/4871721))
  - Avoid rendering authors with `[bot]` in their name ([4f3f644](https://github.com/unjs/changelogen/commit/4f3f644))
  - Format name to avoid duplicates ([f74a988](https://github.com/unjs/changelogen/commit/f74a988))

#### ⚠️  Breaking Changes

  - ⚠️  Resolve github usernames using `ungh/ungh` ([#46](https://github.com/unjs/changelogen/pull/46))

### ❤️  Contributors

- Pooya Parsa ([@pi0](http://github.com/pi0))

## v0.3.5

[compare changes](https://github.com/unjs/changelogen/compare/v0.3.4...v0.3.5)


### 🩹 Fixes

  - Only skip non breaking `chre(deps)` ([20e622e](https://github.com/unjs/changelogen/commit/20e622e))

### ❤️  Contributors

- Pooya Parsa

## v0.3.4

[compare changes](https://github.com/unjs/changelogen/compare/v0.3.3...v0.3.4)


### 🚀 Enhancements

  - Infer github config from package.json ([#37](https://github.com/unjs/changelogen/pull/37))

### ❤️  Contributors

- Pooya Parsa

## v0.3.3

[compare changes](https://github.com/unjs/changelogen/compare/v0.3.2...v0.3.3)


### 🚀 Enhancements

  - Expose `determineSemverChange` and `bumpVersion` ([5451f18](https://github.com/unjs/changelogen/commit/5451f18))

### 🩹 Fixes

  - Let `--output` work without value ([#43](https://github.com/unjs/changelogen/pull/43))
  - Consider docs and refactor as semver patch for bump ([648ccf1](https://github.com/unjs/changelogen/commit/648ccf1))

### 🏡 Chore

  - Manually update old changelog entries ([c3ff561](https://github.com/unjs/changelogen/commit/c3ff561))
  - Update dependencies ([c210976](https://github.com/unjs/changelogen/commit/c210976))
  - Fix typecheck ([8796cf1](https://github.com/unjs/changelogen/commit/8796cf1))

### ❤️  Contributors

- Lvjiaxuan
- Pooya Parsa

## v0.3.2

[compare changes](https://github.com/unjs/changelogen/compare/v0.3.1...v0.3.2)


### 🩹 Fixes

  - Use release version in changelog title ([04671a6](https://github.com/unjs/changelogen/commit/04671a6))

### ❤️  Contributors

- Pooya Parsa

## 0.3.1


### 🚀 Enhancements

  - Handle new version before generating changelog ([fd56f6b](https://github.com/unjs/changelogen/commit/fd56f6b))

### 🩹 Fixes

  - Use `creatordate` to find last tag ([#39](https://github.com/unjs/changelogen/pull/39))

### ❤️  Contributors

- Ahad Birang
- Pooya Parsa

## 0.3.0


### 🚀 Enhancements

  - **cli:** ⚠️  Show changelog in CLI unless bumping or releasing ([d348943](https://github.com/unjs/changelogen/commit/d348943))

#### ⚠️  Breaking Changes

  - **cli:** ⚠️  Show changelog in CLI unless bumping or releasing ([d348943](https://github.com/unjs/changelogen/commit/d348943))

### ❤️  Contributors

- Pooya Parsa

## 0.2.3


### 🩹 Fixes

  - Import semver as default import ([3bd0b61](https://github.com/unjs/changelogen/commit/3bd0b61))

### ❤️  Contributors

- Pooya Parsa

## 0.2.2


### 🚀 Enhancements

  - Generate markdown links when github is provided ([ffe1d08](https://github.com/unjs/changelogen/commit/ffe1d08))

### ✅ Tests

  - Update snapshot ([b264c80](https://github.com/unjs/changelogen/commit/b264c80))

### ❤️  Contributors

- Pooya Parsa

## 0.2.1


### 🩹 Fixes

  - Use last commit for changelog diff (6ac4b4b)
  - Use h2 for title (fc0967c)

### ✅ Tests

  - Update snapshot (102aa98)

### ❤️  Contributors

- Pooya Parsa

## 0.2.0


### 🚀 Enhancements

  - GetGitDiff ignores from (#17)
  - Add gitmoji support (#22)
  - Auto-update changelog files (#24)
  - Support `--bump` to update version while generating changelog (9bf9aff)
  - Basic `--release` support (934c487)

### 🩹 Fixes

  - Expose `./config` (#10)
  - Use `getCurrentGitRef` (#15)
  - **parse:** ⚠️  `references` with type (#27)
  - Convertminor to patch for 0.x versions (011b6a1)
  - Run release step last (b052f55)
  - Handle breaking change commits for bumping (f7ffaa4)
  - Show original semver type without 0.x changes in log (ddd818a)
  - Use `v` prefix for git tag and annotate (bf6b5da)
  - Add missing annotate message (157b0c5)

### 💅 Refactors

  - Use lines array for constructing markdown (#16)

### 🏡 Chore

  - Update lockfile and vitest config (48f609b)
  - Use changelogen release flow (2a8bb4f)

#### ⚠️  Breaking Changes

  - **parse:** ⚠️  `references` with type (#27)

### ❤️  Contributors

- Anthony Fu
- Conner
- Pooya Parsa
- 三咲智子

### 0.1.1


### Bug Fixes

* remove `general` in entries without scope ([31a0861](https://github.com/unjs/changelogen/commit/31a08615bb7da611dcaefe33b510d23aa7d2cc29))

## 0.1.0


### ⚠ BREAKING CHANGES

* use flat scopes

* use flat scopes ([8e33e93](https://github.com/unjs/changelogen/commit/8e33e93e6c4aa4b0b727d351fd73590626d1d6ce))

### 0.0.6

### 0.0.5


### Features

* add missing commitlint types ([#6](https://github.com/unjs/changelogen/issues/6)) ([0a6deef](https://github.com/unjs/changelogen/commit/0a6deefae9a433bbb2136ac8675976ac455dd159))

### 0.0.4


### Bug Fixes

* **cli:** use `/usr/bin/env` (resolves [#5](https://github.com/unjs/changelogen/issues/5)) ([e4218cc](https://github.com/unjs/changelogen/commit/e4218cc08d07b597137469396ba83ec709d7f174))

### 0.0.3


### Features

* generate breaking changes section ([cc0b427](https://github.com/unjs/changelogen/commit/cc0b4272543ffc012d15f038ffa62cdcaca35a44))


### Bug Fixes

* avoid `.exec` for multi matches ([7c612fc](https://github.com/unjs/changelogen/commit/7c612fc4e698e9f8fa1554405efb19b51d7c412f))
* format names for case matching ([ece2d90](https://github.com/unjs/changelogen/commit/ece2d9067171e2b34f45f3d86c28912e90106a6c))

### 0.0.2 (2022-05-02)
