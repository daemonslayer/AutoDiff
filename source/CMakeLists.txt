set(library_name AutoDiff)
add_library(${library_name} SHARED
    autodiff.hpp
)
set_target_properties(${library_name} PROPERTIES LINKER_LANGUAGE CXX)