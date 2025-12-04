load(
    "//xla/tsl/platform:build_config.bzl",
    "tf_proto_library",
)

package(
    # copybara:uncomment default_applicable_licenses = ["//tensorflow:license"],
    licenses = ["notice"],
)

tf_proto_library(
    name = "runtime_proto",
    srcs = ["runtime.proto"],
    create_grpc_library = True,
    make_default_target_header_only = True,
    visibility = ["//visibility:public"],
)
