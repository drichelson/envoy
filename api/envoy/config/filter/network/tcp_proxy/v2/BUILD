load("@envoy_api//bazel:api_build_system.bzl", "api_proto_library_internal", "api_proto_package")

licenses(["notice"])  # Apache 2

api_proto_package(
    deps = [
        "//envoy/api/v2/core",
        "//envoy/config/filter/accesslog/v2:pkg",
    ],
)

api_proto_library_internal(
    name = "tcp_proxy",
    srcs = ["tcp_proxy.proto"],
    deps = [
        "//envoy/api/v2/core:address",
        "//envoy/api/v2/core:base",
        "//envoy/config/filter/accesslog/v2:accesslog",
    ],
)
