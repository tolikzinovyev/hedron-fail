load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "com_google_absl",
    integrity = "sha256-2Vw3v7BP+fXNrVHhkMxd0oKFHDYbczdxfS0uy9dOIB8=",
    strip_prefix = "abseil-cpp-7bd9ff910d489658da58251de1317eb3f790a2c6",
    url = "https://github.com/abseil/abseil-cpp/archive/7bd9ff910d489658da58251de1317eb3f790a2c6.zip",
)

http_archive(
    name = "hedron_compile_commands",
    integrity = "sha256-+yrH5Jj1kqb7Nv+RzNhOuUy5QH7JuJHKGMHkKfGaYwA=",
    strip_prefix = "bazel-compile-commands-extractor-a14ad3a64e7bf398ab48105aaa0348e032ac87f8",
    url = "https://github.com/hedronvision/bazel-compile-commands-extractor/archive/a14ad3a64e7bf398ab48105aaa0348e032ac87f8.zip",
)

load("@hedron_compile_commands//:workspace_setup.bzl", "hedron_compile_commands_setup")

hedron_compile_commands_setup()
