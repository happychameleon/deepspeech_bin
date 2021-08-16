project('binary dep', 'c')

cc =  meson.get_compiler('c')
bin_dep = declare_dependency(dependencies : cc.find_library('deepspeech', dirs : meson.current_source_dir()), include_directories : include_directories('include'))