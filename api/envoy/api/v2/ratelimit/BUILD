load("@envoy_api//bazel:api_build_system.bzl", "api_proto_library_internal", "api_proto_package")

licenses(["notice"])  # Apache 2

api_proto_package()

api_proto_library_internal(
    name = "ratelimit",
    srcs = ["ratelimit.proto"],
    visibility = ["//envoy/api/v2:friends"],
)
