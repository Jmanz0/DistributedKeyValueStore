cc_binary(
    name = "main",
    srcs = ["main.cpp"],
    copts = ["-std=c++17"],
    deps = [
          "@io_opentelemetry_cpp//api",
          "@io_opentelemetry_cpp//exporters/otlp:otlp_exporter",
          "@io_opentelemetry_cpp//sdk/src/trace"
   ],
)
