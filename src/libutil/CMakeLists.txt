# Librspamd-util
SET(LIBRSPAMDUTILSRC
				${CMAKE_CURRENT_SOURCE_DIR}/addr.c
				${CMAKE_CURRENT_SOURCE_DIR}/libev_helper.c
				${CMAKE_CURRENT_SOURCE_DIR}/expression.c
				${CMAKE_CURRENT_SOURCE_DIR}/fstring.c
				${CMAKE_CURRENT_SOURCE_DIR}/hash.c
				${CMAKE_CURRENT_SOURCE_DIR}/mem_pool.c
				${CMAKE_CURRENT_SOURCE_DIR}/printf.c
				${CMAKE_CURRENT_SOURCE_DIR}/radix.c
				${CMAKE_CURRENT_SOURCE_DIR}/regexp.c
				${CMAKE_CURRENT_SOURCE_DIR}/rrd.c
				${CMAKE_CURRENT_SOURCE_DIR}/shingles.c
				${CMAKE_CURRENT_SOURCE_DIR}/sqlite_utils.c
				${CMAKE_CURRENT_SOURCE_DIR}/str_util.c
				${CMAKE_CURRENT_SOURCE_DIR}/upstream.c
				${CMAKE_CURRENT_SOURCE_DIR}/util.c
				${CMAKE_CURRENT_SOURCE_DIR}/heap.c
				${CMAKE_CURRENT_SOURCE_DIR}/multipattern.c
				${CMAKE_CURRENT_SOURCE_DIR}/cxx/utf8_util.cxx
		${CMAKE_CURRENT_SOURCE_DIR}/cxx/rspamd-simdutf.cxx
		${CMAKE_CURRENT_SOURCE_DIR}/cxx/util_tests.cxx
		${CMAKE_CURRENT_SOURCE_DIR}/cxx/file_util.cxx)
# Rspamdutil
SET(RSPAMD_UTIL ${LIBRSPAMDUTILSRC} PARENT_SCOPE)