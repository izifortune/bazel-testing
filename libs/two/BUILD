package(default_visibility=["//visibility:public"])
load("@build_bazel_rules_typescript//:defs.bzl", "ts_library")

ts_library(
    name = "two",
    srcs = glob(["*.ts"]),
    deps = [
      "@npm//@types/node",
        "//libs/one:one",
    ]
)
