# Copyright 2022 The MediaPipe Authors.
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

load(
    "//mediapipe/framework/tool:mediapipe_files.bzl",
    "mediapipe_files",
)

package(
    default_visibility = ["//mediapipe/tasks:internal"],
    licenses = ["notice"],  # Apache 2.0
)

mediapipe_files(srcs = [
    "mobile_ica_8bit-with-metadata.tflite",
    "mobile_ica_8bit-with-unsupported-metadata-version.tflite",
    "mobile_ica_8bit-without-model-metadata.tflite",
    "mobile_object_classifier_v0_2_3-metadata-no-name.tflite",
    "mobilenet_v1_0.25_224_1_default_1.tflite",
    "mobilenet_v2_1.0_224_quant.tflite",
    "mobilenet_v2_1.0_224_quant_without_metadata.tflite",
    "mobilenet_v2_1.0_224_without_metadata.tflite",
])

exports_files([
    "external_file",
    "general_meta.json",
    "golden_json.json",
    "associated_file_meta.json",
    "bounding_box_tensor_meta.json",
    "classification_tensor_float_meta.json",
    "classification_tensor_uint8_meta.json",
    "classification_tensor_unsupported_meta.json",
    "feature_tensor_meta.json",
    "image_tensor_meta.json",
    "input_image_tensor_float_meta.json",
    "input_image_tensor_uint8_meta.json",
    "input_image_tensor_unsupported_meta.json",
    "score_calibration.txt",
    "score_calibration_file_meta.json",
    "score_calibration_tensor_meta.json",
    "score_thresholding_meta.json",
    "labels.txt",
    "mobilenet_v2_1.0_224.json",
    "mobilenet_v2_1.0_224_quant.json",
])

filegroup(
    name = "model_files",
    srcs = [
        "mobile_ica_8bit-with-metadata.tflite",
        "mobile_ica_8bit-with-unsupported-metadata-version.tflite",
        "mobile_ica_8bit-without-model-metadata.tflite",
        "mobile_object_classifier_v0_2_3-metadata-no-name.tflite",
        "mobilenet_v1_0.25_224_1_default_1.tflite",
        "mobilenet_v2_1.0_224_quant.tflite",
        "mobilenet_v2_1.0_224_quant_without_metadata.tflite",
        "mobilenet_v2_1.0_224_without_metadata.tflite",
    ],
)

filegroup(
    name = "data_files",
    srcs = [
        "associated_file_meta.json",
        "bounding_box_tensor_meta.json",
        "classification_tensor_float_meta.json",
        "classification_tensor_uint8_meta.json",
        "classification_tensor_unsupported_meta.json",
        "external_file",
        "feature_tensor_meta.json",
        "general_meta.json",
        "golden_json.json",
        "image_tensor_meta.json",
        "input_image_tensor_float_meta.json",
        "input_image_tensor_uint8_meta.json",
        "input_image_tensor_unsupported_meta.json",
        "labels.txt",
        "mobilenet_v2_1.0_224.json",
        "mobilenet_v2_1.0_224_quant.json",
        "score_calibration.txt",
        "score_calibration_file_meta.json",
        "score_calibration_tensor_meta.json",
        "score_thresholding_meta.json",
    ],
)
