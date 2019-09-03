load('//:subdir_glob.bzl', 'subdir_glob')

cxx_library(
  name = 'rapidcheck',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('include', '**/*.hpp'),
    ('include', '**/*.h'),
  ]),
  headers = subdir_glob([
    ('src', '**/*.h'),
  ]),
  srcs = glob([
    'src/**/*.cpp',
  ]),
  licenses = [
    'LICENSE.md',
  ],
  visibility = [
    'PUBLIC',
  ],
)
