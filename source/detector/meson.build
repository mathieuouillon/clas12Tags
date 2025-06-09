sub_dir_name = meson.current_source_dir().split('/').get(-1)
LD += {
    'name' : sub_dir_name,
    'sources' : files(
        'detector.cc',
        'detector_factory.cc',
        'mysql_det_factory.cc'
    ),
    'headers' : files(
        'detector.h',
        'detector_factory.h',
        'mysql_det_factory.h'
    ),
    'dependencies' : [qt6_deps, clhep_deps, geant4_deps],
}
