LOCAL_PATH := $(call my-dir)
include $(CLEAR_VARS)

LOCAL_MODULE_TAGS := optional

LOCAL_STATIC_JAVA_LIBRARIES := fix comm cor mine am android-support-v4

LOCAL_SRC_FILES := $(call all-java-files-under, src)

LOCAL_SDK_VERSION := current

LOCAL_PACKAGE_NAME := Oschina

LOCAL_CERTIFICATE := abner_key

LOCAL_PROGUARD_ENABLED := disabled

include $(BUILD_PACKAGE)

include $(CLEAR_VARS)

LOCAL_PREBUILT_STATIC_JAVA_LIBRARIES := fix:libs/Android_SDK_v1.2_Fix.jar \
	comm:libs/commons-httpclient-3.1.jar cor:libs/core-2.3.0.jar \
	mine:libs/httpmime-4.1.3.jar am:libs/libammsdk.jar

include $(BUILD_MULTI_PREBUILT)
