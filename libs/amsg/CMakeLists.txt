#
# This file is part of the CMake build system for Gce
#
# CMake auto-generated configuration options. 
# Do not check in modified versions of this file.
#
# Copyright (c) 2009-2014 Nous Xiong (348944179 at qq dot com)
#
# Distributed under the Boost Software License, Version 1.0. (See accompanying
# file LICENSE_1_0.txt or copy at http://www.boost.org/LICENSE_1_0.txt)
#
# See https://github.com/nousxiong/gce for latest version.
#

# All headers need install include dependences.
install (
  DIRECTORY ${PROJECT_SOURCE_DIR}/gce/amsg DESTINATION include/gce
  PATTERN "impl" EXCLUDE
  PATTERN "CVS" EXCLUDE
  PATTERN ".svn" EXCLUDE
  )
