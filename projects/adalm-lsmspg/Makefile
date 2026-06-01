EXAMPLE ?= iio_example

IIOD = y

ifneq ($(findstring max32665,$(TARGET)),)
NO_OS_USB_UART = y
endif

include ../../tools/scripts/generic_variables.mk

include ../../tools/scripts/examples.mk

include src.mk

include ../../tools/scripts/generic.mk
