

set(support_source_files
 filesystem.cpp
 timing.cpp
)

add_library(support STATIC ${support_source_files})

SET_TARGET_PROPERTIES( support PROPERTIES COMPILE_FLAGS -fPIC)