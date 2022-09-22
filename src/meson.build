src_files = [
  'aco.c',
  'acosw.S',
]

header_files = [
  'aco.h',
]

libaco = both_libraries('aco', src_files, install: true)
install_headers(header_files)

libaco_dep = declare_dependency(
  sources: header_files,
  link_with: libaco,
  include_directories: include_directories('.'),
)
