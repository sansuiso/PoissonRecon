add_executable(PoissonRecon PoissonRecon.cpp)
target_sources(PoissonRecon PRIVATE PlyFile.cpp)

add_executable(SSDRecon SSDRecon.cpp)
target_sources(SSDRecon PRIVATE PlyFile.cpp)

add_executable(SurfaceTrimmer SurfaceTrimmer.cpp)
target_sources(SurfaceTrimmer PRIVATE PlyFile.cpp)