##
## This file is part of the libopencm3 project.
##
## Copyright (C) 2020 Lubomir Rintel <lkundrak@v3.sk>
##
## This library is free software: you can redistribute it and/or modify
## it under the terms of the GNU Lesser General Public License as published by
## the Free Software Foundation, either version 3 of the License, or
## (at your option) any later version.
##
## This library is distributed in the hope that it will be useful,
## but WITHOUT ANY WARRANTY; without even the implied warranty of
## MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
## GNU Lesser General Public License for more details.
##
## You should have received a copy of the GNU Lesser General Public License
## along with this library.  If not, see <http://www.gnu.org/licenses/>.
##

OBJS = ssd1306.o console.o gud.o systick.o

BINARY = usb-display

LDSCRIPT = $(OPENCM3_DIR)/lib/stm32/f1/stm32f103x8.ld

VPATH += ../../../../gd32v/f103/polos-alef/$(BINARY)

include ../../Makefile.include

