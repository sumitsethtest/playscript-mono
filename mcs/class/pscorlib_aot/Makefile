thisdir = class/pscorlib_aot
include ../../build/rules.make

LIBRARY = pscorlib_aot.dll
LIBRARY_SNK = ../mono.snk
LIBRARY_PACKAGE = none

LIB_MCS_FLAGS = -keyfile:$(LIBRARY_SNK) -r:System.dll -r:System.Core.dll -r:PlayScript.Dynamic_aot.dll -r:System.Xml.dll -r:ICSharpCode.SharpZipLib.dll

NO_TEST = yes

include ../../build/library.make
