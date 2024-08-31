## [Bazel tips2](https://docs.google.com/presentation/d/1vNuuY97NmxP85MLEheYcMDHbpFb6cwSYWPNloBqdrPM/edit?usp=sharing)
1. bazel run would invoke build
2. bazel native rules (not written in starlark)
3. Bazel custom rules can be loaded using load function - load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
4. @bazel_tools - label

## Commands used
1. bazel run //project:Hello

## Bazel directories
1. bazel-out in symlink
    1. /private/var/tmp/_bazel_mohannarayanaswamy/b1cb78c3c1e1c1627056eb72f6f34e34/execroot/_main/bazel-out
1. bazel-bin in symlink
    1. /private/var/tmp/_bazel_mohannarayanaswamy/b1cb78c3c1e1c1627056eb72f6f34e34/execroot/_main/bazel-out/darwin_arm64-fastbuild/bin
1. bazel-testlos
    1. /private/var/tmp/_bazel_mohannarayanaswamy/b1cb78c3c1e1c1627056eb72f6f34e34/execroot/_main/bazel-out/darwin_arm64-fastbuild/testlogs
1. bazel-WORKSPACE
    1. /private/var/tmp/_bazel_mohannarayanaswamy/b1cb78c3c1e1c1627056eb72f6f34e34/execroot/_main    