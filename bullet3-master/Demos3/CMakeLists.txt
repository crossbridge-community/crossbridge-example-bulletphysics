if (OPENGL_FOUND)
if (BUILD_OPENGL3_DEMOS)
	SUBDIRS( AllBullet2Demos GpuDemos SimpleOpenGL3 )
endif(BUILD_OPENGL3_DEMOS)
endif(OPENGL_FOUND)
