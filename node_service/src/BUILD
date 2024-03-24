cc_binary(
    name = "node_service",
    srcs = ["node_service.cpp"],
#    hdrs = ["node_service.h"],
    deps = [
        "@leveldb//:leveldb",
        "@io_opentelemetry_cpp//api",
        "@io_opentelemetry_cpp//exporters/otlp:otlp_exporter",
        "@io_opentelemetry_cpp//sdk/src/trace",
    ],
)