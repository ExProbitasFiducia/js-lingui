# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [3.14.0](https://github.com/lingui/js-lingui/compare/v3.13.3...v3.14.0) (2022-06-22)


### Bug Fixes

* Fix error read properties of undefined ([#1239](https://github.com/lingui/js-lingui/issues/1239)) ([8dd2398](https://github.com/lingui/js-lingui/commit/8dd2398e0d1fdce1663b8aee391f6ab2208be77b))





## [3.13.3](https://github.com/lingui/js-lingui/compare/v3.13.2...v3.13.3) (2022-04-24)

**Note:** Version bump only for package @lingui/cli





## [3.13.2](https://github.com/lingui/js-lingui/compare/v3.13.1...v3.13.2) (2022-01-24)

**Note:** Version bump only for package @lingui/cli





## [3.13.1](https://github.com/lingui/js-lingui/compare/v3.13.0...v3.13.1) (2022-01-21)


### Bug Fixes

* cloud service `import()` on case-sensitive filesystems ([#1174](https://github.com/lingui/js-lingui/issues/1174)) ([5feb120](https://github.com/lingui/js-lingui/commit/5feb120e8c75d7b8c082d5c4b68185ef5dcc3ebc))





# [3.13.0](https://github.com/lingui/js-lingui/compare/v3.12.1...v3.13.0) (2021-11-26)


### Bug Fixes

* pin cli-table to 0.3.6 ([#1172](https://github.com/lingui/js-lingui/issues/1172)) ([b659b18](https://github.com/lingui/js-lingui/commit/b659b1802054d76862663decd9ef49d983e0304e))
* **cli:** extract with --overwrite should fallback to key ([#1166](https://github.com/lingui/js-lingui/issues/1166)) ([e5e9d59](https://github.com/lingui/js-lingui/commit/e5e9d598a2f1a27845b414d8be1927b84f3d8e9c))
* Allow pseudoLocalize to work in @lingui/loader ([#1165](https://github.com/lingui/js-lingui/issues/1165)) ([356c224](https://github.com/lingui/js-lingui/commit/356c224530a0fde730b31602eb6f95c7496f245e))
* don't push pseudoLocale to translation.io provider ([#1161](https://github.com/lingui/js-lingui/issues/1161)) ([5d2186b](https://github.com/lingui/js-lingui/commit/5d2186bccf7721aaef8573a6a6e9764f00c107e6))
* stripping origin if line numbers already strippped ([#1143](https://github.com/lingui/js-lingui/issues/1143)) ([82a3265](https://github.com/lingui/js-lingui/commit/82a32655d2cd362ec4d7164822585cbd3ae5dd6e))


### Features

* **cli:** make extract cmd asynchronous execution ([#1170](https://github.com/lingui/js-lingui/issues/1170)) ([f99d8b1](https://github.com/lingui/js-lingui/commit/f99d8b17f3f05c3caef9481feb142f0b35916f91))
* msgctxt support ([#1094](https://github.com/lingui/js-lingui/issues/1094)) ([8ee42cb](https://github.com/lingui/js-lingui/commit/8ee42cbfe26bc6d055748dcf2713ab8ade7ec827))





## [3.12.1](https://github.com/lingui/js-lingui/compare/v3.12.0...v3.12.1) (2021-09-28)

**Note:** Version bump only for package @lingui/cli





# [3.12.0](https://github.com/lingui/js-lingui/compare/v3.11.1...v3.12.0) (2021-09-28)


### Bug Fixes

* **#1137:** configPath is passed through babel-plugin-extract-messages ([#1140](https://github.com/lingui/js-lingui/issues/1140)) ([8921156](https://github.com/lingui/js-lingui/commit/89211567632733cf9955cafc9c92bd87c6154852)), closes [#1137](https://github.com/lingui/js-lingui/issues/1137)





## [3.11.1](https://github.com/lingui/js-lingui/compare/v3.11.0...v3.11.1) (2021-09-07)


### Bug Fixes

* cli and conf needed hotfix for [#1110](https://github.com/lingui/js-lingui/issues/1110) ([1c6378d](https://github.com/lingui/js-lingui/commit/1c6378daa84f77757f99f6e592f6cb0e1fe02ebd))





# [3.11.0](https://github.com/lingui/js-lingui/compare/v3.10.4...v3.11.0) (2021-09-07)


### Bug Fixes

* 'compile --watch' not watching for correct file based on format ([#1088](https://github.com/lingui/js-lingui/issues/1088)) ([ab68c06](https://github.com/lingui/js-lingui/commit/ab68c06775c37bf5960536f274ed35fb2420f6a8))
* add extract-template for po-gettext format ([#1089](https://github.com/lingui/js-lingui/issues/1089)) ([ea00f55](https://github.com/lingui/js-lingui/commit/ea00f551cbae2ae7596f7fe3055cb8442863f53a))
* country-coded language breaks plurals with po-gettext ([#1131](https://github.com/lingui/js-lingui/issues/1131)) ([6b60b8a](https://github.com/lingui/js-lingui/commit/6b60b8af20e7a8e4e74354a870aaa8ef0d25d1e8))
* extractors CLI validation and accept require and require.resolve ([#1126](https://github.com/lingui/js-lingui/issues/1126)) ([c50a06e](https://github.com/lingui/js-lingui/commit/c50a06eac65d71853ec2c29905a0c4883a5cc70d))
* fallbackLocales to false causing unexpected behaviour ([#1123](https://github.com/lingui/js-lingui/issues/1123)) ([60e3952](https://github.com/lingui/js-lingui/commit/60e3952f9e99a6d21992821bff573e42f6ecf5fd))
* keys with leading number was generating bad object keys ([#1127](https://github.com/lingui/js-lingui/issues/1127)) ([8bb2983](https://github.com/lingui/js-lingui/commit/8bb2983fa93e024ba2cb3d2f63262d2495755755))
* no files being found when catalogs.include has more than one entry ([#1108](https://github.com/lingui/js-lingui/issues/1108)) ([04efd85](https://github.com/lingui/js-lingui/commit/04efd85ab5bae72607c06672f5c8da809a45dbcb))
* wrong detect whether a translation is plural ([#1119](https://github.com/lingui/js-lingui/issues/1119)) ([48b6644](https://github.com/lingui/js-lingui/commit/48b6644f56d66a80d08ca9d95faca8c04d47eba0))


### Features

* Add debounce option to compile and extract CLI ([#1101](https://github.com/lingui/js-lingui/issues/1101)) ([a13334c](https://github.com/lingui/js-lingui/commit/a13334ceba850bfd50818d66551877867b86d655))
* Cloud service providers & Translation.io ([#1107](https://github.com/lingui/js-lingui/issues/1107)) ([cbc87b5](https://github.com/lingui/js-lingui/commit/cbc87b5dab8daf0cd2217b2a2525dfd12dad7272))





## [3.10.4](https://github.com/lingui/js-lingui/compare/v3.10.3...v3.10.4) (2021-06-16)

**Note:** Version bump only for package @lingui/cli





## [3.10.3](https://github.com/lingui/js-lingui/compare/v3.10.2...v3.10.3) (2021-06-14)

**Note:** Version bump only for package @lingui/cli





## [3.10.2](https://github.com/lingui/js-lingui/compare/v3.10.1...v3.10.2) (2021-06-08)


### Bug Fixes

* remoteLoader should return an object instead of export ([d461695](https://github.com/lingui/js-lingui/commit/d46169598e4b43c5fb5cb686f9b1e8811292e9c6))





## [3.10.1](https://github.com/lingui/js-lingui/compare/v3.10.0...v3.10.1) (2021-06-08)

**Note:** Version bump only for package @lingui/cli





# [3.10.0](https://github.com/lingui/js-lingui/compare/v3.9.0...v3.10.0) (2021-06-08)


### Bug Fixes

* po-gettext format issues with CLI ([#1073](https://github.com/lingui/js-lingui/issues/1073)) ([a529aca](https://github.com/lingui/js-lingui/commit/a529aca239b232926b786811f9ac03c9b771417b))
* use correct case for PO file header MIME-Version ([#1074](https://github.com/lingui/js-lingui/issues/1074)) ([f31afc5](https://github.com/lingui/js-lingui/commit/f31afc53837f0e67660d2825125f74fc11db8e0b))


### Features

* load remote catalogs with remoteLoader() ([#1080](https://github.com/lingui/js-lingui/issues/1080)) ([e73a4b3](https://github.com/lingui/js-lingui/commit/e73a4b34cf8d83a45044c220148761d79b4fd8a9))





# [3.9.0](https://github.com/lingui/js-lingui/compare/v3.8.10...v3.9.0) (2021-05-18)


### Bug Fixes

* lineNumbers false was removing the entire origin ([#1060](https://github.com/lingui/js-lingui/issues/1060)) ([2d25f2c](https://github.com/lingui/js-lingui/commit/2d25f2c5d8f7c624250a1218f83cbe43433c264b))


### Features

* configurable and extendable extractors with Lingui config ([#1065](https://github.com/lingui/js-lingui/issues/1065)) ([263ee59](https://github.com/lingui/js-lingui/commit/263ee59163c94220f5ba3999aa60ca40dc352e0c))





## [3.8.10](https://github.com/lingui/js-lingui/compare/v3.8.9...v3.8.10) (2021-04-19)

**Note:** Version bump only for package @lingui/cli





## [3.8.9](https://github.com/lingui/js-lingui/compare/v3.8.8...v3.8.9) (2021-04-09)

**Note:** Version bump only for package @lingui/cli





## [3.8.8](https://github.com/lingui/js-lingui/compare/v3.8.7...v3.8.8) (2021-04-09)

**Note:** Version bump only for package @lingui/cli





## [3.8.7](https://github.com/lingui/js-lingui/compare/v3.8.6...v3.8.7) (2021-04-09)

**Note:** Version bump only for package @lingui/cli





## [3.8.6](https://github.com/lingui/js-lingui/compare/v3.8.5...v3.8.6) (2021-04-08)

**Note:** Version bump only for package @lingui/cli





## [3.8.5](https://github.com/lingui/js-lingui/compare/v3.8.4...v3.8.5) (2021-04-08)


### Bug Fixes

* improve compile log error if bad syntax on the string ([9b2705f](https://github.com/lingui/js-lingui/commit/9b2705feada95f5272346bacee54a26b5518af5e))





## [3.8.4](https://github.com/lingui/js-lingui/compare/v3.8.3...v3.8.4) (2021-04-08)

**Note:** Version bump only for package @lingui/cli





## [3.8.3](https://github.com/lingui/js-lingui/compare/v3.8.2...v3.8.3) (2021-04-05)

**Note:** Version bump only for package @lingui/cli





## [3.8.2](https://github.com/lingui/js-lingui/compare/v3.8.1...v3.8.2) (2021-03-31)

**Note:** Version bump only for package @lingui/cli





## [3.8.1](https://github.com/lingui/js-lingui/compare/v3.8.0...v3.8.1) (2021-03-23)

**Note:** Version bump only for package @lingui/cli





# [3.8.0](https://github.com/lingui/js-lingui/compare/v3.7.2...v3.8.0) (2021-03-23)


### Bug Fixes

* selectOrdinal pseudolocalize insensitive ([16acafe](https://github.com/lingui/js-lingui/commit/16acafe42a2ae1c33200ab9b89bc7a17db69897d))


### Features

* allow to disable lineNumbers ([#1007](https://github.com/lingui/js-lingui/issues/1007)) ([fe67e0f](https://github.com/lingui/js-lingui/commit/fe67e0f7986188bff2c102703c4df3507506e0f2))





## [3.7.2](https://github.com/lingui/js-lingui/compare/v3.7.1...v3.7.2) (2021-03-14)


### Bug Fixes

* lingui extract ignores custom directories as args [#998](https://github.com/lingui/js-lingui/issues/998) ([f426881](https://github.com/lingui/js-lingui/commit/f426881d2b6fb51de06ed43159f56b67a36e2ece))





## [3.7.1](https://github.com/lingui/js-lingui/compare/v3.7.0...v3.7.1) (2021-03-07)

**Note:** Version bump only for package @lingui/cli





# [3.7.0](https://github.com/lingui/js-lingui/compare/v3.6.0...v3.7.0) (2021-03-04)


### Bug Fixes

* @lingui/cli type error when catalog is missing ([#988](https://github.com/lingui/js-lingui/issues/988)) ([8c44af2](https://github.com/lingui/js-lingui/commit/8c44af2442f979ae60de8059e68436508cdc8f74))
* Report correct number of missing messages in strict mode ([#992](https://github.com/lingui/js-lingui/issues/992)) ([128f3e2](https://github.com/lingui/js-lingui/commit/128f3e237daef838e18e73818fc681609e4bc131))
* use pkgUp.sync to localize package.json ([#985](https://github.com/lingui/js-lingui/issues/985)) ([18d985d](https://github.com/lingui/js-lingui/commit/18d985dd414276d07a1f7ffc7e21ffa5e0dadc36))





# [3.6.0](https://github.com/lingui/js-lingui/compare/v3.5.1...v3.6.0) (2021-02-23)


### Features

* --watch mode for extract and compile ([#974](https://github.com/lingui/js-lingui/issues/974)) ([a4f90ee](https://github.com/lingui/js-lingui/commit/a4f90ee1cedf3726908104f535b9a8985a444363))





## [3.5.1](https://github.com/lingui/js-lingui/compare/v3.5.0...v3.5.1) (2021-02-09)

**Note:** Version bump only for package @lingui/cli





# [3.5.0](https://github.com/lingui/js-lingui/compare/v3.4.0...v3.5.0) (2021-02-02)


### Bug Fixes

* <Select /> pseudolocalization ([#961](https://github.com/lingui/js-lingui/issues/961)) ([f1e1a25](https://github.com/lingui/js-lingui/commit/f1e1a25acd654c9877147ce3f40bc827bc54987a))
* message when translations are missing ([#964](https://github.com/lingui/js-lingui/issues/964)) ([14f24f2](https://github.com/lingui/js-lingui/commit/14f24f2725771dcea0793de146abc9b86ea88789))
* NODE_ENV=production crashes lingui extract [#952](https://github.com/lingui/js-lingui/issues/952) ([f368b35](https://github.com/lingui/js-lingui/commit/f368b353e975dab4024b755eb9d70f48b535a693))
* obsolete flag disable when using extract [files] ([#967](https://github.com/lingui/js-lingui/issues/967)) ([0ea63e9](https://github.com/lingui/js-lingui/commit/0ea63e9a0b5cd2463fca18621e6dba16642f4d00))
* React macros fixes ([#958](https://github.com/lingui/js-lingui/issues/958)) ([353c537](https://github.com/lingui/js-lingui/commit/353c5379a22473293aafcb4651db387e72c82a7a))
* **docs:** documentation-typos ([#955](https://github.com/lingui/js-lingui/issues/955)) ([f73cb8c](https://github.com/lingui/js-lingui/commit/f73cb8c09d9919489f5fbb9a539da30faae53004))


### Features

* Introduced @lingui/snowpack-plugin ([#947](https://github.com/lingui/js-lingui/issues/947)) ([96bd31b](https://github.com/lingui/js-lingui/commit/96bd31b54d5ebfa2e28c96e14ee92d43b4199ae5))





# [3.4.0](https://github.com/lingui/js-lingui/compare/v3.3.0...v3.4.0) (2021-01-13)


### Bug Fixes

* compilerBabelOptions warning with jest-validate ([#938](https://github.com/lingui/js-lingui/issues/938)) ([087ec1f](https://github.com/lingui/js-lingui/commit/087ec1fe45076bcfc8ea3a6f7657f39bbe1c1d58))
* Use LINGUI_CONFIG env as fallback for extract ([#932](https://github.com/lingui/js-lingui/issues/932)) ([ce71a8b](https://github.com/lingui/js-lingui/commit/ce71a8bc6f7b7bb9d1f3c46d473dc5e700a6b6b5))


### Features

* Lingui compiles to typescript files ([#942](https://github.com/lingui/js-lingui/issues/942)) ([10bce7d](https://github.com/lingui/js-lingui/commit/10bce7dc890f208dc71bcf81dc34e57d389544fe))





# [3.3.0](https://github.com/lingui/js-lingui/compare/v3.2.3...v3.3.0) (2020-12-08)


### Bug Fixes

* accept pseudolocalization in SelectOrdinal ([#903](https://github.com/lingui/js-lingui/issues/903)) ([d4c24bf](https://github.com/lingui/js-lingui/commit/d4c24bf6bbb1a6eeb651b1a70490b10f502a28c6))
* formatters exceptions throw error ([#889](https://github.com/lingui/js-lingui/issues/889)) ([d6b774c](https://github.com/lingui/js-lingui/commit/d6b774cf53dd4bf691a228d3f05edaea2442b121))
* plural pseudolocalization with offset ([#887](https://github.com/lingui/js-lingui/issues/887)) ([3d54b4d](https://github.com/lingui/js-lingui/commit/3d54b4d9b10b731733a385306263de2da08100ec))


### Features

* config accepts compilerBabelOptions ([#906](https://github.com/lingui/js-lingui/issues/906)) ([38d01ef](https://github.com/lingui/js-lingui/commit/38d01ef13a7867460b68ab709f94a17176a21f25))
* extract messages from specific files ([#881](https://github.com/lingui/js-lingui/issues/881)) ([82dea5f](https://github.com/lingui/js-lingui/commit/82dea5f35b55cbb039a48e49fc94dbfbbaca7df9))
* Implement gettext plurals for PO files ([#677](https://github.com/lingui/js-lingui/issues/677)) ([415b90e](https://github.com/lingui/js-lingui/commit/415b90e0abfb24bb7170a5ba7630a4ead94898dd))





## [3.2.3](https://github.com/lingui/js-lingui/compare/v3.2.2...v3.2.3) (2020-11-22)

**Note:** Version bump only for package @lingui/cli





## [3.2.2](https://github.com/lingui/js-lingui/compare/v3.2.1...v3.2.2) (2020-11-20)


### Bug Fixes

* locale not present in catalogs warn ([6f598e8](https://github.com/lingui/js-lingui/commit/6f598e81bb3278722b995d69daad3f5cdc492284))





# [3.2.0](https://github.com/lingui/js-lingui/compare/v3.1.0...v3.2.0) (2020-11-12)


### Bug Fixes

* absolute rootDir on Windows ([#853](https://github.com/lingui/js-lingui/issues/853)) ([f4eabf9](https://github.com/lingui/js-lingui/commit/f4eabf9fdfa04d23009dda00717344e161f1f8f7))


### Features

* extract multiple comments per translation ID ([#854](https://github.com/lingui/js-lingui/issues/854)) ([c849c9c](https://github.com/lingui/js-lingui/commit/c849c9c024832aa7b07e5f837791e287c3aebe29))





# [3.1.0](https://github.com/lingui/js-lingui/compare/v3.0.3...v3.1.0) (2020-11-10)


### Bug Fixes

* accept catalog paths without ending slash ([#812](https://github.com/lingui/js-lingui/issues/812)) ([5d39586](https://github.com/lingui/js-lingui/commit/5d3958638913d5f6b6d318bf21ce4f3019a69e88))
* fix exit code on compile --strict errors ([#825](https://github.com/lingui/js-lingui/issues/825)) ([69a80e2](https://github.com/lingui/js-lingui/commit/69a80e2b0b5061c657e63835355207be199db692))


### Features

* add cli option to extract only a specific locale ([#816](https://github.com/lingui/js-lingui/issues/816)) ([49f45b2](https://github.com/lingui/js-lingui/commit/49f45b24a58f79e1f6de9c279b0c033d593d7854))
* enable pseudolocalization from pseudolocale folder ([#836](https://github.com/lingui/js-lingui/issues/836)) ([f1e0078](https://github.com/lingui/js-lingui/commit/f1e0078b9892cd7a95a6ad8105f1a3b41bc3b88b))
* lookup lingui command suggestions in package.json ([#823](https://github.com/lingui/js-lingui/issues/823)) ([d58dc09](https://github.com/lingui/js-lingui/commit/d58dc09554cb7054a3463b9f1b53297338322d66))
* use fallback locales from cldr ([#820](https://github.com/lingui/js-lingui/issues/820)) ([2d9e124](https://github.com/lingui/js-lingui/commit/2d9e124b91f1ba7a65e9f997a3ba952679c6c23a))
