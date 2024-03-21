<h1 align="center">Krank data collection</h1>


This organization houses a curated collection of datasets related to sleep,
dreams, and cognition.

Each repository here contains Python code that downloads,
preprocesses, and repackages text and/or neuroscientific data.
The curated data are then published as GitHub release artifacts.

---

<h2 align="center">Versioning</h2>

Datasets in this collection **use only a single number to denote their versions**.
This is because any change to data/metadata can lead to code that relies on them
breaking, so [semantic versioning](https://semver.org/) wouldn't make sense.
New releases are made when data/metadata are changed, added, or deleted.

That being said, an optional **pre-release versioning** might be specified
during development. When curating a dataset, one might want to test the dataset
out for a bit before releasing it more formally. In these cases,
[SemVer Specificiation 9](https://semver.org/#spec-item-9) is followed. Any
pre-release should be denoted with an `-alpha.X` tag, where `X` starts at 1 and
increases as needed. For example, release order might look like:

* `v1-alpha.1`
* `v1-alpha.2`
* `v1-alpha.3`
* `v1`
* `v2`
* `v3-alpha.1`
* `v3`