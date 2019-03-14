# OpenXR-Registry

The OpenXR-Registry repository contains the OpenXR API and Extension
Registry, including generated specifications and reference pages, and
reference cards. The sources for these documents are mostly found in the
separate https://github.com/KhronosGroup/OpenXR-Docs repository; this
repository is used as a backing store for the web view of the registry at
https://www.khronos.org/registry/openxr/ . Commits to the master branch of
OpenXR-Registry will be reflected in the web view.

Interesting files in this repository include:

* index.php - toplevel index page for the web view. This relies on PHP
  include files found elsewhere on www.khronos.org and so is not very useful
  in isolation.
* specs/0.90/ - OpenXR 0.90 Provisional API specifications and reference pages and API
  reference card.
