licenses(["notice"])

filegroup(
    name = "ios_sim_template",
    srcs = ["ios_sim.template.sh"],
    visibility = ["//visibility:public"],
)

# Consumed by bazel tests.
filegroup(
    name = "for_bazel_tests",
    testonly = 1,
    srcs = glob(["**"]),
    visibility = [
        "//apple:__subpackages__",
    ],
)
