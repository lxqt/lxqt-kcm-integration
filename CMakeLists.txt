cmake_minimum_required(VERSION 3.0.2 FATAL_ERROR)

project(lxqt-theme-debian)

set(LXQTBT_MINIMUM_VERSION "0.1.0")

find_package(lxqt-build-tools ${LXQTBT_MINIMUM_VERSION} REQUIRED)

include(GNUInstallDirs)
include(LXQtTranslateDesktop)
include(LXQtConfigVars)

add_subdirectory(applications)
add_subdirectory(lxqt)
add_subdirectory(pcmanfm-qt)
add_subdirectory(qterminal.org)
add_subdirectory(themes)
add_subdirectory(xfce4)
