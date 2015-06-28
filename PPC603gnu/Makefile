# Wind River Workbench generated Makefile.
# Do not edit!!!
#
# The file ".wrmakefile" is the template used by the Wind River Workbench to
# generate the makefiles of this project. Add user-specific build targets and
# make rules only(!) in this project's ".wrmakefile" file. These will then be
# automatically dumped into the makefiles.

WIND_HOME := $(subst \,/,$(WIND_HOME))
WIND_BASE := $(subst \,/,$(WIND_BASE))
WIND_USR := $(subst \,/,$(WIND_USR))

all : pre_build main_all post_build

_clean ::
	@echo "make: removing targets and objects of `pwd`"

TRACE=0
TRACEON=$(TRACE:0=@)
TRACE_FLAG=$(TRACEON:1=)

MAKEFILE := Makefile

FLEXIBLE_BUILD := 1

BUILD_SPEC = PPC603gnu
DEBUG_MODE = 1
ifeq ($(DEBUG_MODE),1)
MODE_DIR := Debug
else
MODE_DIR := NonDebug
endif
OBJ_DIR := .
WS_ROOT_DIR := C:/WindRiver/Workspace
PRJ_ROOT_DIR := $(WS_ROOT_DIR)/Entropy2014\ 4th\ of\ July



#Global Build Macros
PROJECT_TYPE = DKM
DEFINES = 
EXPAND_DBG = 0


#BuildSpec specific Build Macros
VX_CPU_FAMILY = ppc
CPU = PPC603
TOOL_FAMILY = gnu
TOOL = gnu
TOOL_PATH = 
CC_ARCH_SPEC = -mcpu=603 -mstrict-align -mno-implicit-fp -mlongcall
LIBPATH = 
LIBS = 

IDE_INCLUDES = -I$(WIND_BASE)/target/h/WPILib -I$(WIND_BASE)/target/h -I$(WIND_BASE)/target/h/wrn/coreip 

IDE_LIBRARIES = $(WIND_BASE)/target/lib/WPILib.a 

IDE_DEFINES = 



#BuildTool flags
ifeq ($(DEBUG_MODE),1)
DEBUGFLAGS_C-Compiler = -g
DEBUGFLAGS_C++-Compiler = -g
DEBUGFLAGS_Linker = -g
DEBUGFLAGS_Partial-Image-Linker = 
DEBUGFLAGS_Librarian = 
DEBUGFLAGS_Assembler = -g
else
DEBUGFLAGS_C-Compiler = -O2 -fstrength-reduce -fno-builtin
DEBUGFLAGS_C++-Compiler = -O2 -fstrength-reduce -fno-builtin
DEBUGFLAGS_Linker = -O2 -fstrength-reduce -fno-builtin
DEBUGFLAGS_Partial-Image-Linker = 
DEBUGFLAGS_Librarian = 
DEBUGFLAGS_Assembler = -O2 -fstrength-reduce -fno-builtin
endif


#Project Targets
PROJECT_TARGETS = Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Entropy2014\ 4th\ of\ July.out


#Rules

# Entropy2014 4th of July
ifeq ($(DEBUG_MODE),1)
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : DEBUGFLAGS_C-Compiler = -g
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : DEBUGFLAGS_C++-Compiler = -g
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : DEBUGFLAGS_Linker = -g
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : DEBUGFLAGS_Partial-Image-Linker = 
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : DEBUGFLAGS_Librarian = 
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : DEBUGFLAGS_Assembler = -g
else
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : DEBUGFLAGS_C-Compiler = -O2 -fstrength-reduce -fno-builtin
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : DEBUGFLAGS_C++-Compiler = -O2 -fstrength-reduce -fno-builtin
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : DEBUGFLAGS_Linker = -O2 -fstrength-reduce -fno-builtin
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : DEBUGFLAGS_Partial-Image-Linker = 
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : DEBUGFLAGS_Librarian = 
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : DEBUGFLAGS_Assembler = -O2 -fstrength-reduce -fno-builtin
endif
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : IDE_INCLUDES = -I$(WIND_BASE)/target/h/WPILib -I$(WIND_BASE)/target/h -I$(WIND_BASE)/target/h/wrn/coreip 
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : IDE_LIBRARIES = $(WIND_BASE)/target/lib/WPILib.a 
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : IDE_DEFINES = 
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : PROJECT_TYPE = DKM
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : DEFINES = 
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : EXPAND_DBG = 0
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : VX_CPU_FAMILY = ppc
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : CPU = PPC603
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : TOOL_FAMILY = gnu
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : TOOL = gnu
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : TOOL_PATH = 
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : CC_ARCH_SPEC = -mcpu=603 -mstrict-align -mno-implicit-fp -mlongcall
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : LIBPATH = 
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : LIBS = 
Entropy2014\ 4th\ of\ July/$(MODE_DIR)/% : OBJ_DIR := Entropy2014\ 4th\ of\ July/$(MODE_DIR)

Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/AcquisitionArms.o : $(PRJ_ROOT_DIR)/AcquisitionArms.cpp $(FORCE_FILE_BUILD)
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)ccppc $(DEBUGFLAGS_C++-Compiler) $(CC_ARCH_SPEC) -ansi -Wall  -MD -MP -mlongcall $(ADDED_C++FLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL   $(DEFINES) -o "$@" -c "$<"


Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/Autonomy.o : $(PRJ_ROOT_DIR)/Autonomy.cpp $(FORCE_FILE_BUILD)
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)ccppc $(DEBUGFLAGS_C++-Compiler) $(CC_ARCH_SPEC) -ansi -Wall  -MD -MP -mlongcall $(ADDED_C++FLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL   $(DEFINES) -o "$@" -c "$<"


Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/Controller.o : $(PRJ_ROOT_DIR)/Controller.cpp $(FORCE_FILE_BUILD)
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)ccppc $(DEBUGFLAGS_C++-Compiler) $(CC_ARCH_SPEC) -ansi -Wall  -MD -MP -mlongcall $(ADDED_C++FLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL   $(DEFINES) -o "$@" -c "$<"


Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/EntropyCamera.o : $(PRJ_ROOT_DIR)/EntropyCamera.cpp $(FORCE_FILE_BUILD)
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)ccppc $(DEBUGFLAGS_C++-Compiler) $(CC_ARCH_SPEC) -ansi -Wall  -MD -MP -mlongcall $(ADDED_C++FLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL   $(DEFINES) -o "$@" -c "$<"


Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/EntropyCompressor.o : $(PRJ_ROOT_DIR)/EntropyCompressor.cpp $(FORCE_FILE_BUILD)
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)ccppc $(DEBUGFLAGS_C++-Compiler) $(CC_ARCH_SPEC) -ansi -Wall  -MD -MP -mlongcall $(ADDED_C++FLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL   $(DEFINES) -o "$@" -c "$<"


Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/EntropyDrive.o : $(PRJ_ROOT_DIR)/EntropyDrive.cpp $(FORCE_FILE_BUILD)
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)ccppc $(DEBUGFLAGS_C++-Compiler) $(CC_ARCH_SPEC) -ansi -Wall  -MD -MP -mlongcall $(ADDED_C++FLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL   $(DEFINES) -o "$@" -c "$<"


Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/EntropyInfraredSensor.o : $(PRJ_ROOT_DIR)/EntropyInfraredSensor.cpp $(FORCE_FILE_BUILD)
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)ccppc $(DEBUGFLAGS_C++-Compiler) $(CC_ARCH_SPEC) -ansi -Wall  -MD -MP -mlongcall $(ADDED_C++FLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL   $(DEFINES) -o "$@" -c "$<"


Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/EntropyJoystick.o : $(PRJ_ROOT_DIR)/EntropyJoystick.cpp $(FORCE_FILE_BUILD)
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)ccppc $(DEBUGFLAGS_C++-Compiler) $(CC_ARCH_SPEC) -ansi -Wall  -MD -MP -mlongcall $(ADDED_C++FLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL   $(DEFINES) -o "$@" -c "$<"


Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/EntropyRangeFinder.o : $(PRJ_ROOT_DIR)/EntropyRangeFinder.cpp $(FORCE_FILE_BUILD)
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)ccppc $(DEBUGFLAGS_C++-Compiler) $(CC_ARCH_SPEC) -ansi -Wall  -MD -MP -mlongcall $(ADDED_C++FLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL   $(DEFINES) -o "$@" -c "$<"


Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/EntropyRobot2014.o : $(PRJ_ROOT_DIR)/EntropyRobot2014.cpp $(FORCE_FILE_BUILD)
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)ccppc $(DEBUGFLAGS_C++-Compiler) $(CC_ARCH_SPEC) -ansi -Wall  -MD -MP -mlongcall $(ADDED_C++FLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL   $(DEFINES) -o "$@" -c "$<"


Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/ExampleSHS.o : $(PRJ_ROOT_DIR)/ExampleSHS.cpp $(FORCE_FILE_BUILD)
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)ccppc $(DEBUGFLAGS_C++-Compiler) $(CC_ARCH_SPEC) -ansi -Wall  -MD -MP -mlongcall $(ADDED_C++FLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL   $(DEFINES) -o "$@" -c "$<"


Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/Kicker.o : $(PRJ_ROOT_DIR)/Kicker.cpp $(FORCE_FILE_BUILD)
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)ccppc $(DEBUGFLAGS_C++-Compiler) $(CC_ARCH_SPEC) -ansi -Wall  -MD -MP -mlongcall $(ADDED_C++FLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL   $(DEFINES) -o "$@" -c "$<"


OBJECTS_Entropy2014-4th-of-July = Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/AcquisitionArms.o \
	 Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/Autonomy.o \
	 Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/Controller.o \
	 Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/EntropyCamera.o \
	 Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/EntropyCompressor.o \
	 Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/EntropyDrive.o \
	 Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/EntropyInfraredSensor.o \
	 Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/EntropyJoystick.o \
	 Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/EntropyRangeFinder.o \
	 Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/EntropyRobot2014.o \
	 Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/ExampleSHS.o \
	 Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/Kicker.o

Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Entropy2014\ 4th\ of\ July.out : $(OBJECTS_Entropy2014-4th-of-July)
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@";rm -f "$@";nmppc $(OBJECTS_Entropy2014-4th-of-July) $(IDE_LIBRARIES) | tclsh $(WIND_BASE)/host/resource/hutils/tcl/munch.tcl -c ppc > $(OBJ_DIR)/ctdt.c; $(TOOL_PATH)ccppc $(DEBUGFLAGS_Linker) $(CC_ARCH_SPEC) -fdollars-in-identifiers -Wall $(ADDED_CFLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -DCPU=$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL   $(DEFINES)  -o $(OBJ_DIR)/ctdt.o -c $(OBJ_DIR)/ctdt.c; $(TOOL_PATH)ccppc -r -nostdlib -Wl,-X -T $(WIND_BASE)/target/h/tool/gnu/ldscripts/link.OUT -o "$@" $(OBJ_DIR)/ctdt.o $(OBJECTS_Entropy2014-4th-of-July) $(IDE_LIBRARIES) $(LIBPATH) $(LIBS)  $(ADDED_LIBPATH) $(ADDED_LIBS) && if [ "$(EXPAND_DBG)" = "1" ]; then plink "$@";fi

Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Entropy2014\ 4th\ of\ July_compile_file : $(FILE) ;

_clean :: Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Entropy2014\ 4th\ of\ July_clean

Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Entropy2014\ 4th\ of\ July_clean : 
	$(TRACE_FLAG)if [ -d "Entropy2014 4th of July" ]; then cd "Entropy2014 4th of July"; rm -rf $(MODE_DIR); fi

force : 

DEP_FILES := Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/AcquisitionArms.d Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/Autonomy.d Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/Controller.d \
	 Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/EntropyCamera.d Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/EntropyCompressor.d Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/EntropyDrive.d \
	 Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/EntropyInfraredSensor.d Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/EntropyJoystick.d Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/EntropyRangeFinder.d \
	 Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/EntropyRobot2014.d Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/ExampleSHS.d Entropy2014\ 4th\ of\ July/$(MODE_DIR)/Objects/Entropy2014\ 4th\ of\ July/Kicker.d
-include $(DEP_FILES)



-include $(PRJ_ROOT_DIR)/*.makefile

-include *.makefile

main_all : external_build $(PROJECT_TARGETS)
	@echo "make: built targets of `pwd`"

# entry point for extending the build
external_build ::
	@echo ""

# main entry point for pre processing prior to the build
pre_build :: $(PRE_BUILD_STEP) generate_sources
	@echo ""

# entry point for generating sources prior to the build
generate_sources ::
	@echo ""

# main entry point for post processing after the build
post_build :: $(POST_BUILD_STEP) deploy_output
	@echo ""

# entry point for deploying output after the build
deploy_output ::
	@echo ""

clean :: external_clean $(CLEAN_STEP) _clean

# entry point for extending the build clean
external_clean ::
	@echo ""
