AM_CXXFLAGS = -Wall -Werror -std=c++11 -I$(top_srcdir)/include

##############################
# Unit tests
##############################
TESTS = all_tests
check_PROGRAMS = all_tests
all_tests_CXXFLAGS = $(AM_CXXFLAGS) -I$(top_srcdir)/unittests
all_tests_LDFLAGS = -lpthread
all_tests_SOURCES = unittests/gtest/src/gtest-all.cc unittests/gtest/src/gtest_main.cc unittests/gtest/gtest.h

all_tests_SOURCES += unittests/test_48bit_index.cc unittests/test_compact_vector.cc
