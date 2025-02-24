# Changelog

## 2.3.3-11 (2022/09/23)

* Fix Dockerfile with new Alpine Edge packages
* Remove riscv64 architecture
* Update AmuleWebUI-Reloaded theme
* Commit Changelog.md

## 2.3.3-10 (2022/08/29)

* Overwrite the passwords if environment variables are set
* Remove linux/386 architecture
* Add linux/riscv64 architecture

## 2.3.3-9 (2022/07/28)

* Rebuild with latest base Docker Image

## 2.3.3-8 (2022/06/03)

* Update GeoLiteCountryUpdateUrl and StatsServerURL URLs
* Rebuild with latest base Docker Image

## 2.3.3-7 (2022/02/19)

* Fix MOD_AUTO_RESTART starting multiple cron tasks
* Use su command instead of sudo to run aMule
* Require obfuscation by default (IsClientCryptLayerRequired=1)
* Increase slot upload speed to 50 KB/s = 400Kb/s by default (SlotAllocation=50)

## 2.3.3-6 (2022/02/13)

* Use pre-compiled packages to improve Docker build time
* Include man documentation

## 2.3.3-5 (2022/02/13)

* Replace Docker base image with Alpine 3.15
* Remove support for mips64le arch, include arm/v6 arch
* Add auto restart mod. MOD_AUTO_RESTART
* Add auto share mod. MOD_AUTO_SHARE
* Add fix kad graph mod. MOD_FIX_KAD_GRAPH

## 2.3.3-4 (2022/01/15)

* Update base Docker image
* Do not remove dead ED2K servers (RemoveDeadServer=0)

## 2.3.3-3 (2022/01/09)

* Install locales and set en_US.UTF-8 Resolves #4
* Change default Ed2kServersUrl to emule-security.org

## 2.3.3-2 (2021/07/04)

* Docker image size is halved
* Update base Docker image

## 2.3.3-1 (2021/06/06)

* First release
* aMule 2.3.3 from Debian Bullseye
* Add AmuleWebUI-Reloaded theme
* Fix issue amule-project/amule#265
