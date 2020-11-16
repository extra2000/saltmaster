# Changelog

## [2.0.0-alpha.1](https://github.com/extra2000/saltmaster-box/compare/v1.2.6...v2.0.0-alpha.1) (2020-11-16)


### ⚠ BREAKING CHANGES

* **vagrant:** Existing Vagrantfile have been renamed into example Vagrant file. Also port forwarding has been disabled by default and can be re-enabled by uncomment port forwarding lines in the Vagrant file.
* **salt/etc/:** Salt Master config file `salt/etc/saltmaster-box` has been renamed to `salt/etc/saltmaster-box.example`.

### Features

* **salt/roots/:** Add user customizable `formulas/`, `pillars/`, and `salts/` directory ([713d874](https://github.com/extra2000/saltmaster-box/commit/713d8747cf66f934822fe44e5c75df32f664b82b))
* **vagrant:** Add Debian 10 `x86_64` box ([1239e54](https://github.com/extra2000/saltmaster-box/commit/1239e54c04bcaa2332fabe65de498e605302e2c9))
* **vagrant:** Add Fedora 32 `x86_64` box ([9e9412d](https://github.com/extra2000/saltmaster-box/commit/9e9412d5f0f3ffda3c06146c4815fc5940d20f62))
* **vagrant:** Add openSUSE Leap 15.2 `aarch64` box ([51a1652](https://github.com/extra2000/saltmaster-box/commit/51a16521de9edb22d7f27f44b13d71a7a0430761))
* **vagrant:** Add openSUSE Leap 15.2 `aarch64` QEMU box ([bacf3b0](https://github.com/extra2000/saltmaster-box/commit/bacf3b0f047ab2d2c835365df257f4f895a6b418))
* **vagrant:** Add openSUSE Leap 15.2 `x86_64` box ([bf591b8](https://github.com/extra2000/saltmaster-box/commit/bf591b82ed6f6e64b613a9207a1743e01818f0ba))
* **vagrant:** Add openSUSE Tumbleweed `aarch64` box ([a432311](https://github.com/extra2000/saltmaster-box/commit/a432311a05bb5d095ec55100fdc2fe4535833fed))
* **vagrant:** Add openSUSE Tumbleweed `aarch64` QEMU box ([3db0fbd](https://github.com/extra2000/saltmaster-box/commit/3db0fbd818efd348ee9edbcbd559a6c5e113d2e1))
* **vagrant:** Add openSUSE Tumbleweed `x86_64` box ([3399b98](https://github.com/extra2000/saltmaster-box/commit/3399b9837e4e36b85875e8abdaf29eb950d53fe6))
* **vagrant:** Add Ubuntu 20.04 `x86_64` box ([7ac32fc](https://github.com/extra2000/saltmaster-box/commit/7ac32fc908f3b3237278a45ebd560923ae36df3d))


### Code Refactoring

* **salt/etc/:** Rename `salt/etc/saltmaster-box` to `salt/etc/saltmaster-box.example` ([43b9d56](https://github.com/extra2000/saltmaster-box/commit/43b9d564f5cda43f1b784972b38722e4850a6f0f))
* **vagrant:** Rename existing Vagrant file into example Vagrant file ([a778f12](https://github.com/extra2000/saltmaster-box/commit/a778f127ff9799fc56a69f9c62cd0e8bb1f19e2b))


### Documentations

* **README:** Add instruction to choose Vagrant file before creating Vagrant box ([7bf80cf](https://github.com/extra2000/saltmaster-box/commit/7bf80cf72df6d1630a45c0f4c1d3b3592ef6f677))
* **README:** Add instruction to create Salt Master config file from the example file ([eb6b3f1](https://github.com/extra2000/saltmaster-box/commit/eb6b3f1f86906b1f297a803350e768b13ab162fb))


### Continuous Integrations

* Add instruction to create Vagrant file and Salt Master config file ([ff444be](https://github.com/extra2000/saltmaster-box/commit/ff444bef95f7d8626b548d18bba62ec1bb011afb))

### [1.2.6](https://github.com/extra2000/saltmaster-box/compare/v1.2.5...v1.2.6) (2020-10-05)


### Continuous Integrations

* **semantic-release:** Fix patch updates with BREAKING CHANGE doesn't trigger major release ([ad26627](https://github.com/extra2000/saltmaster-box/commit/ad26627cea523b69569b9901900f65b57e3777ab))

### [1.2.5](https://github.com/extra2000/saltmaster-box/compare/v1.2.4...v1.2.5) (2020-10-02)


### Continuous Integrations

* **semantic-release:** Add fix type ([aa35927](https://github.com/extra2000/saltmaster-box/commit/aa35927f96f0ca3a33abfd9eec4186fce159f1e5))

### [1.2.4](https://github.com/extra2000/saltmaster/compare/v1.2.3...v1.2.4) (2020-10-01)


### Documentations

* **CHANGELOG:** Rename saltmaster to saltmaster-box ([18f034a](https://github.com/extra2000/saltmaster/commit/18f034a56b40d8d73864a081e7c1b88ad836cf43))
* **README:** Rename saltmaster to saltmaster-box ([2945c6d](https://github.com/extra2000/saltmaster/commit/2945c6d5dd16e469b9e7fd3609da4d5d527c954e))


### Continuous Integrations

* **semantic-release:** Add feat type ([d695094](https://github.com/extra2000/saltmaster/commit/d695094ddc23ef37a0c3bb091a317d033ce5061e))
* **semantic-release:** Add rc, beta, and alpha release channels ([46c3ed8](https://github.com/extra2000/saltmaster/commit/46c3ed87ad9af9abe7bf0d6e6e85488c869e5f89))
* **semantic-release:** Remove invalid release branches ([57d6f0d](https://github.com/extra2000/saltmaster/commit/57d6f0d35bf81c82940b8f707c5aa1a23274962c))
* **semantic-release:** Remove scope README from docs ([8c26f47](https://github.com/extra2000/saltmaster/commit/8c26f47410aef1a10a0af29e06524b7dd594ddd0))

### [1.2.3](https://github.com/extra2000/saltmaster-box/compare/v1.2.2...v1.2.3) (2020-09-26)


### Continuous Integrations

* **travis:** Change Slack notifications token ([b5be05b](https://github.com/extra2000/saltmaster-box/commit/b5be05b66a5274719e1f561dedb23409e9604004))

### [1.2.2](https://github.com/extra2000/saltmaster-box/compare/v1.2.1...v1.2.2) (2020-09-26)


### Continuous Integrations

* **travis:** Add slack notifications ([c246a01](https://github.com/extra2000/saltmaster-box/commit/c246a01fe7626ca77fd13a71e89cc8095483a25e))

### [1.2.1](https://github.com/extra2000/saltmaster-box/compare/v1.2.0...v1.2.1) (2020-09-26)


### Continuous Integrations

* **semantic-release:** Add @commitlint/cli and @commitlint/config-conventional ([9148574](https://github.com/extra2000/saltmaster-box/commit/91485742b6c4e2a81e91f09510ce406f4d2bbe44))
* **semantic-release:** Replace .releaserc from extra2000/openfortivpn ([9aa133d](https://github.com/extra2000/saltmaster-box/commit/9aa133dce468b05ec8744e0eda44d39ae1cd8c4e))
