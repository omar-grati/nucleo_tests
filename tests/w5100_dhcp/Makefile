#
# Copyright (c) 2015 Francesco Balducci
#
# This file is part of nucleo_tests.
#
#    nucleo_tests is free software: you can redistribute it and/or modify
#    it under the terms of the GNU Lesser General Public License as published by
#    the Free Software Foundation, either version 3 of the License, or
#    (at your option) any later version.
#
#    nucleo_tests is distributed in the hope that it will be useful,
#    but WITHOUT ANY WARRANTY; without even the implied warranty of
#    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
#    GNU Lesser General Public License for more details.
#
#    You should have received a copy of the GNU Lesser General Public License
#    along with nucleo_tests.  If not, see <http://www.gnu.org/licenses/>.
#

BINARY = w5100_dhcp_test
OBJS += $(ROOT_DIR)/src/dhcp_client.o
OBJS += $(ROOT_DIR)/src/w5100_dhcp.o
OBJS += $(ROOT_DIR)/src/w5100_socket.o
OBJS += $(ROOT_DIR)/src/w5100_spi.o
OBJS += $(ROOT_DIR)/src/inet.o
OBJS += $(ROOT_DIR)/src/stdio_usart.o
OBJS += $(ROOT_DIR)/src/syscalls.o
OBJS += $(ROOT_DIR)/src/file.o
OBJS += $(ROOT_DIR)/src/timespec.o
OBJS += $(ROOT_DIR)/src/clock_gettime_systick.o
OBJS += $(ROOT_DIR)/src/sleep.o
OBJS += $(ROOT_DIR)/src/nanosleep.o
OBJS += $(ROOT_DIR)/src/clock_nanosleep_poll.o
LDLIBS_SYS =

CPPFLAGS += -DW5100_NO_STATIC_IP

include ../test.mk

