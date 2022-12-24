include_directories("./")
add_executable (SpaceInvaderz "SpaceInvaderz.cpp" "SpaceInvaderz.h" "Window/Window.h" "Window/Window.cpp")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET SpaceInvaderz PROPERTY CXX_STANDARD 20)
endif()
