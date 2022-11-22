# CMakeList.txt: Rest++ için CMake projesi, kaynağı ekleyin ve tanımlayın
# projeye özgü mantık burada bulunur.
#

# Kaynağı bu projenin yürütülebilir dosyasına ekleyin.
add_executable (Rest++ "Rest++.cpp" "Rest++.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET Rest++ PROPERTY CXX_STANDARD 20)
endif()

# TODO: Gerekirse testleri ve yükleme hedeflerini ekleyin.
