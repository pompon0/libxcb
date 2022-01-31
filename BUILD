package(
    default_visibility = ["//visibility:public"],
)

cc_library(
  name = "xcb",
  defines = ["HAVE_CONFIG_H"],
  srcs = glob(["xcb/*.c"]),
  hdrs = glob(["xcb/*.h"]),
  includes = ["."],
  deps = ["@libxau//:Xau"],
)
