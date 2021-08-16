project('deepspeech', 'c')

cc =  meson.get_compiler('c')
deepspeech = declare_dependency(dependencies : cc.find_library('deepspeech', dirs : meson.current_source_dir()), include_directories : include_directories('include'))
