project('ffmpeg-drm', 'c')

dep_drm = dependency('libdrm')
dep_avcodec = dependency('libavcodec')
dep_avutil = dependency('libavutil')

executable('ffmpeg-drm', 'main.c', dependencies: [dep_drm, dep_avcodec, dep_avutil], install : true)
