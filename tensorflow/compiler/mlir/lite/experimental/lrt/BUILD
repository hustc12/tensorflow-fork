# Copyright 2024 Google LLC.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

package(
    # copybara:uncomment default_applicable_licenses = ["//tensorflow:license"],
    default_visibility = ["//tensorflow/compiler/mlir/lite/experimental/lrt:__subpackages__"],
)

cc_library(
    name = "lite_rt_common",
    srcs = ["lite_rt_common.cc"],
    hdrs = ["lite_rt_common.h"],
)

cc_library(
    name = "lite_rt_support",
    hdrs = ["lite_rt_support.h"],
    deps = [":lite_rt_common"],
)

cc_library(
    name = "lite_rt_op_code",
    hdrs = ["lite_rt_op_code.h"],
    deps = ["//tensorflow/lite:builtin_ops"],
)
