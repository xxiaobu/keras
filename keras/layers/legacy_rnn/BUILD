# Description:
#   Contains the legacy TF RNN APIs (internal TensorFlow version).

package(
    default_visibility = [
        "//keras:friends",
        "//third_party/tensorflow:__subpackages__",
    ],
    licenses = ["notice"],
)

py_library(
    name = "rnn_cell_impl",
    srcs = ["rnn_cell_impl.py"],
    srcs_version = "PY3",
    deps = [
        ":rnn_cell_wrapper_impl",
        "//:expect_tensorflow_installed",
        "//keras:activations",
        "//keras/engine:input_spec",
        "//keras/initializers",
        "//keras/legacy_tf_layers:layers_base",
        "//keras/saving",
        "//keras/utils:tf_utils",
    ],
)

py_library(
    name = "rnn_cell_wrapper_impl",
    srcs = ["rnn_cell_wrapper_impl.py"],
    srcs_version = "PY3",
    deps = [
        "//:expect_tensorflow_installed",
        "//keras/utils:generic_utils",
    ],
)
