noinst_PROGRAMS += ndc_test

ndc_test_sources = %D%/main.cxx
ndc_test_SOURCES = $(ndc_test_sources)

ndc_test_LDADD = $(liblog4cplus_la_file)

if BUILD_WITH_WCHAR_T_SUPPORT
noinst_PROGRAMS += ndc_testU
ndc_testU_CPPFLAGS = $(AM_CPPFLAGS) -DUNICODE=1
ndc_testU_SOURCES = $(ndc_test_sources)
ndc_testU_LDADD = $(liblog4cplusU_la_file)
endif
