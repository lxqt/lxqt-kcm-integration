cmake_minimum_required(VERSION 3.0.2 FATAL_ERROR)

project(lxqt-kcm-integration)

set(LXQTBT_MINIMUM_VERSION "0.1.0")

find_package(lxqt-build-tools ${LXQTBT_MINIMUM_VERSION} REQUIRED)

include(GNUInstallDirs)
include(LXQtTranslateDesktop)
include(LXQtConfigVars)

add_subdirectory(applications)
