TOP = ..
include $(TOP)/configure/CONFIG

DIRS += netCDFSrc

DIRS += jpegSrc

DIRS += zlibSrc

DIRS += tiffSrc
tiffSrc_DEPEND_DIRS += zlibSrc

DIRS += xml2Src

DIRS += szipSrc

DIRS += hdf5Src
hdf5Src_DEPEND_DIRS += szipSrc zlibSrc

DIRS += nexusSrc
nexusSrc_DEPEND_DIRS += hdf5Src

include $(TOP)/configure/RULES_DIRS

