IF(HAVE_ATOMSPACE)
    ADD_SUBDIRECTORY (agents)
    ADD_SUBDIRECTORY (atomtypes)
    ADD_SUBDIRECTORY (module)
ENDIF(HAVE_ATOMSPACE)

IF(HAVE_ATTENTION)
    #ADD_SUBDIRECTORY (hopfield)
ENDIF(HAVE_ATTENTION)

