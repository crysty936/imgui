
set(source_files
    imgui.cpp
    imgui.h
    imgui_demo.cpp
    imgui_draw.cpp
    imgui_internal.h
    imgui_widgets.cpp
    imstb_rectpack.h
    imstb_textedit.h
    imstb_truetype.h
	imgui_tables.cpp
)

add_library(imgui STATIC ${source_files})

target_include_directories(imgui PUBLIC "${CMAKE_CURRENT_LIST_DIR}")