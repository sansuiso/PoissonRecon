set(POISSONRECON_SRC PoissonRecon.cpp PlyFile.cpp)
add_executable(PoissonRecon ${POISSONRECON_SRC})

set(SSDRECON_SRC SSDRecon.cpp PlyFile.cpp)
add_executable(SSDRecon ${SSDRECON_SRC})

set(SURFACETRIMMER_SRC SurfaceTrimmer.cpp PlyFile.cpp)
add_executable(SurfaceTrimmer ${SURFACETRIMMER_SRC})