INCLUDE_DIRECTORIES( ${JPEG_INCLUDE_DIR} )

SET(TARGET_SRC
    EXIF_Orientation.cpp
    ReaderWriterJPEG.cpp
)

SET(TARGET_LIBRARIES_VARS JPEG_LIBRARIES )
#### end var setup  ###
SETUP_PLUGIN(jpeg)
