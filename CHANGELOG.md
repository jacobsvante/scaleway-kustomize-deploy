# Changelog

## [0.3.0](https://github.com/jacobsvante/scaleway-kustomize-deploy-action/compare/v0.2.3...v0.3.0) (2022-08-29)


### Features

* Support deleting successful jobs pre-deploy ([8048f53](https://github.com/jacobsvante/scaleway-kustomize-deploy-action/commit/8048f5356e4436a4ac4848b297f42f53243670e8))

## [0.2.3](https://github.com/jacobsvante/scaleway-kustomize-deploy-action/compare/v0.2.2...v0.2.3) (2022-08-29)


### Bug Fixes

* Remove unnecessary kubectl commands ([ba60438](https://github.com/jacobsvante/scaleway-kustomize-deploy-action/commit/ba60438c473dd8634eaf5cc6323cce0aef1ab8c1))

## [0.2.2](https://github.com/jacobsvante/scaleway-kustomize-deploy-action/compare/v0.2.1...v0.2.2) (2022-08-26)


### Bug Fixes

* Logic error in step "Decrypt secrets with `age`" ([b695c38](https://github.com/jacobsvante/scaleway-kustomize-deploy-action/commit/b695c382a2b2da252bce0e293164b3a2926c778c))

## [0.2.1](https://github.com/jacobsvante/scaleway-kustomize-deploy-action/compare/v0.2.0...v0.2.1) (2022-08-16)


### Bug Fixes

* Look for existing Secret in correct Namespace ([c291be7](https://github.com/jacobsvante/scaleway-kustomize-deploy-action/commit/c291be79dae49396db130671e1d8e332ab20b080))

## [0.2.0](https://github.com/jacobsvante/scaleway-kustomize-deploy-action/compare/v0.1.1...v0.2.0) (2022-08-16)


### ⚠ BREAKING CHANGES

* Use k8s namespace for image pull secret

### Features

* Add input to set kubectl apply/create --dry-run ([7513f3a](https://github.com/jacobsvante/scaleway-kustomize-deploy-action/commit/7513f3a33974c35e4579e0602c3397c7417ee6d0))


### Bug Fixes

* Use k8s namespace for image pull secret ([06e4070](https://github.com/jacobsvante/scaleway-kustomize-deploy-action/commit/06e407032c85c8857557e77606e795603b616933))

## [0.1.1](https://github.com/jacobsvante/scaleway-kustomize-deploy-action/compare/v0.1.0...v0.1.1) (2022-08-11)


### Bug Fixes

* Fix reference to non-existent env var ([cf89613](https://github.com/jacobsvante/scaleway-kustomize-deploy-action/commit/cf89613c75780f92b046a485c5ed7811b961e0a9))
* Missing version.txt ([7b2e7c6](https://github.com/jacobsvante/scaleway-kustomize-deploy-action/commit/7b2e7c6f8a23c5485d18bd503b613c964bb5b186))

## 0.1.0 (2022-08-11)


### Bug Fixes

* Fix reference to non-existent env var ([cf89613](https://github.com/jacobsvante/scaleway-kustomize-deploy-action/commit/cf89613c75780f92b046a485c5ed7811b961e0a9))
* Initial commit ([0069d9d](https://github.com/jacobsvante/scaleway-kustomize-deploy-action/commit/0069d9dd6e9f3a77ce134387eb961efca7364bb2))

## 0.1.0 (2022-08-11)


### Bug Fixes

* Initial commit ([0069d9d](https://github.com/jacobsvante/scaleway-kustomize-deploy-action/commit/0069d9dd6e9f3a77ce134387eb961efca7364bb2))
