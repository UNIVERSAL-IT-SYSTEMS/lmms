FILE(GLOB PNG_FILES *.png)
LIST(SORT PNG_FILES)
INSTALL(FILES ${PNG_FILES} DESTINATION "${LMMS_DATA_DIR}/backgrounds")
