CMAKE_MINIMUM_REQUIRED ( VERSION 2.6)

PROJECT( v8-perf-plugin )

ADD_LIBRARY (v8-perf-plugin SHARED
	../src/libperf.c)
