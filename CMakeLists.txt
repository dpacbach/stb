add_library( stb INTERFACE )
add_library( stb::stb ALIAS stb )

# We don't need much in this file because this library is only
# headers.
target_include_directories(
  stb
  INTERFACE
  ${CMAKE_CURRENT_SOURCE_DIR}
)
