# Copyright (C) 2014 Tai Chi Minh Ralph Eastwood.
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with Flymir LuaDist.
# Please note that the package source code is licensed under its own license.

project ( luafun C )
cmake_minimum_required ( VERSION 2.8 )
include ( cmake/dist.cmake )
include ( lua )

install_lua_module ( fun fun.lua )
install_data ( README.md COPYING.md CONTRIBUTING.md )
