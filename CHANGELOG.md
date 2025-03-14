SatelliteToolboxTransformations.jl Changelog
============================================

Version 0.1.4
-------------

- ![Enhancement][badge-enhancement] We updated the dependency compatibility bounds.
- ![Enhancement][badge-enhancement] We forced specialization in the function
  `sv_ecef_to_ecef`, reducing the allocations due to compilation. (PR [#2][gh-pr-2])

Version 0.1.3
-------------

- ![Feature][badge-feature] We added the functions `ecef_to_geocentric` and
  `geocentric_to_ecef` to convert between ECEF vectors and Geocentric coordinates.

Version 0.1.2
-------------

- ![Bugfix][badge-bugfix] We fixed a bug that was failing the task that builds the stable
  documentation.

Version 0.1.1
-------------

- ![Info][badge-info] The functions related to orbit anomalies were transferred to
  **SatelliteToolboxBase.jl**. These functions are re-exported here. Hence, this
  modifications is note breaking from this package point of view.

Version 0.1.0
-------------

- Initial version.
  - This version was based on the functions in **SatelliteToolbox.jl**.

[badge-breaking]: https://img.shields.io/badge/BREAKING-red.svg
[badge-deprecation]: https://img.shields.io/badge/Deprecation-orange.svg
[badge-feature]: https://img.shields.io/badge/Feature-green.svg
[badge-enhancement]: https://img.shields.io/badge/Enhancement-blue.svg
[badge-bugfix]: https://img.shields.io/badge/Bugfix-purple.svg
[badge-info]: https://img.shields.io/badge/Info-gray.svg

[gh-pr-2]: https://github.com/JuliaSpace/SatelliteToolboxTransformations.jl/pull/2
