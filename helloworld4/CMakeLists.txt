PROJECT(HELLO)
ADD_SUBDIRECTORY(src)

INSTALL(PROGRAMS runhello.sh DESTINATION bin)
INSTALL(FILES README DESTINATION share/doc/${PROJECT_NAME})
INSTALL(DIRECTORY doc/ DESTINATION share/doc/${PROJECT_NAME})