include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'property-tree', 
  header_only = True,
  header_namespace = 'boost/property_tree', 
  exported_headers = subdir_glob([
    ('include/boost/property_tree', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
