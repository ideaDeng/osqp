set(pardiso_includes
    ${CMAKE_CURRENT_SOURCE_DIR}
    PARENT_SCOPE
)

# Set source files
set(
    pardiso_sources
    ${CMAKE_CURRENT_SOURCE_DIR}/pardiso.h
    ${CMAKE_CURRENT_SOURCE_DIR}/pardiso.c
    ${CMAKE_CURRENT_SOURCE_DIR}/pardiso_loader.h
    ${CMAKE_CURRENT_SOURCE_DIR}/pardiso_loader.c
    PARENT_SCOPE
)
