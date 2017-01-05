## List executables to build
noinst_PROGRAMS = test

## .h files for all templates
HFILES_TEMPLATES =

## .cc files for all templates
CCFILES_TEMPLATES =

## .h files for all non-templates
HFILES =

## .cc files for all non-templates
CCFILES = \
	test.cc

## all the source files that are compiled into the
test_SOURCES = \
	$(HFILES) \
	$(CCFILES)

## These are the files that will get installed into the includes directory
## Should include all .h files and the .cc for all templates.
include_HEADERS = \
	$(HFILES) \
	$(HFILES_TEMPLATES) \
	$(CCFILES_TEMPLATES)
