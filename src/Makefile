# Author: crifan
# Date: 2012-05-16
#
# -----------------------------------------------------------------
#  generate output from DocBook sources
#  this is entry makefile for docbook
# -----------------------------------------------------------------
# run this makefile under src directory:
# [office]
# pwd = /home/CLi/develop/docbook/books/xxx/src
# [home]
# pwd = /cygdrive/e/Dev_Root/docbook/dev/books/xxx/src

################################################################################
# Project Settings
################################################################################

# also means main source file name
PROJECT_NAME = virtualbox_tutorial
SUB_SRC_FILES = \
    preface.xml \
    ch01_virtualbox_intro.xml \
    ch02_download_install_virtualbox.xml \
    ch03_common_settings_issues.xml \
    ch04_create_vm_common_steps.xml \
    ch05_create_windows_vm.xml \
    ch06_create_linux_vm.xml \
    ch07_create_mac_vm.xml \
    reference.xml \

DOCBOOK_MAKEFILE_ROOT = ../../../config
################################################################################
# Include docbook makefile
################################################################################
include $(DOCBOOK_MAKEFILE_ROOT)/docbook.mk