project('vala lib', 'vala', 'c')

deps = [
    dependency('glib-2.0'),
    dependency('gee-0.8'),
    dependency('gio-2.0'),
]

filecheck_lib = shared_library('filecheck', 'filecheck.vala',
                  vala_header: 'filecheck.h',
                  vala_vapi: 'filecheck.vapi',
                  dependencies: deps,
                  install: true,
                  install_dir: [true, true, true])
