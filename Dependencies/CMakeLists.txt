include(FetchContent)

message(STATUS "Fetching VTIL-Core (this might take a while)...")
FetchContent_Declare(
    VTIL-Core
    GIT_REPOSITORY https://github.com/vtil-project/VTIL-Core
    GIT_TAG        6f21abb3d4734d1d1a194d879b8d3f1518d4ec4e
    GIT_SHALLOW    false
)
FetchContent_MakeAvailable(VTIL-Core)
