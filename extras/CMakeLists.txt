add_subdirectory(usd)
if (${PXR_BUILD_IMAGING} AND NOT IOS)
    add_subdirectory(imaging)
endif()
