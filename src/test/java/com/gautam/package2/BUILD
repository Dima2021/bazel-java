load("//bzl:test.bzl", "junit4_test_suite")

junit4_test_suite(
    name = "AllTests",
    size = "small",
    srcs = glob([
        "*Test.java",
        "*ITCase.java",
    ]),
    deps = [
        "//src/main/java/com/gautam/package2",
        "@maven//:com_google_guava_guava",
        "@maven//:junit_junit",
    ],
)
