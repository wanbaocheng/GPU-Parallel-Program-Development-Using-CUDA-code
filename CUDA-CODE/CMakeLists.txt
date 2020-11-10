project(imflipG CXX CUDA)
set(CMAKE_CUDA_STANDARD 14)
add_executable(imedgeG imedgeG.cu)
add_executable(imedgeGCM imedgeGCM.cu)