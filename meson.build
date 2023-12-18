project(
    'vic-lab',
    'cpp',
    default_options : ['cpp_std=c++20']
)

source = [
    'vic-lab.cpp'
]

sdbusplus_dep = dependency('sdbusplus')

executable(
    'vic-lab',
    source,
    dependencies:sdbusplus_dep,
    install : true
)