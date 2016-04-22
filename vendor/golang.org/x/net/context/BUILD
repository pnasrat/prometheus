load("@io_bazel_rules_go//go:def.bzl", "go_library")

package(
    default_visibility = ["//visibility:public"],
)

go_library(
    name = "context",
    srcs = ["context.go"]
)

go_library(
    name = "ctxhttp",
    srcs = [
        "ctxhttp/ctxhttp.go",
        "ctxhttp/cancelreq.go",
    ]
)
