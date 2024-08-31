# What is the importance of the WORKSPACE file?
#
# The WORKSPACE file is used to declare external dependencies
# and to define workspace-level options. It is loaded before
# the BUILD files in the workspace, so it can be used to
# define functions and macros that can be used in the BUILD

workspace(name = "bazel_battle")



load("functions.bzl", "get_joke_allowed")
build_name="BazelBattle"

print(build_name)
print(get_joke_allowed(build_name))