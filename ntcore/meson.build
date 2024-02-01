subdir('src/main/native/cpp')

ntcore_inc = include_directories('src/main/native/cpp', 'src/main/native/include')

libntcore = library(
    'ntcore',
    nt_sources,
    include_directories: ntcore_inc
)

libntcore_inc = include_directories('src/main/native/include')

libntcore_dep = declare_dependency(include_directories: libntcore_inc, link_with libntcore)