project(
    'dmabuf-sharing', 
    'c',
    default_options: [
        'buildtype=debugoptimized', 
        'c_std=c11'],
    version: '1.0',
)

dep = [dependency('libdrm'), dependency('libv4l2')]

executable(
    'dmabuf-sharing',
    'dmabuf-sharing.c',

    dependencies: dep,
    install: true,
)
