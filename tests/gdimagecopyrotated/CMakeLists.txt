IF(PNG_FOUND)
LIST(APPEND TESTS_FILES
	bug00020
)
ENDIF(PNG_FOUND)

ADD_GD_TESTS()
