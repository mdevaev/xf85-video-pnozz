AM_CFLAGS = $(XORG_CFLAGS) $(PCIACCESS_CFLAGS)

pnozz_drv_la_LTLIBRARIES = pnozz_drv.la
pnozz_drv_la_LDFLAGS = -module -avoid-version
pnozz_drv_la_LIBADD = $(XORG_LIBS)
pnozz_drv_ladir = @moduledir@/drivers

pnozz_drv_la_SOURCES = \
		compat-api.h \
		pnozz.h \
		pnozz_accel.c \
		pnozz_cursor.c \
		pnozz_driver.c \
		pnozz_exa.c \
		pnozz_regs.h
