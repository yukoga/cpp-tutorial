cc_test(
  name = "hello-test",
  srcs = ["hello-test.cc"],
  copts = [
    "-Iexternal/gtest/googletest/include",
  ],
  deps = [
    "@gtest//:main",
    "//lib:hello-greet",
  ],
)
