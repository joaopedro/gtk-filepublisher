NULL = 

#Build in these directories:

SUBDIRS = \
	src \
	po \
	$(NULL)

gtk_filepublisherdocdir = ${prefix}/doc/gtk_filepublisher
gtk_filepublisherdoc_DATA = \
	ChangeLog \
	README \
	COPYING \
	AUTHORS \
	INSTALL \
	NEWS\
	$(NULL)

EXTRA_DIST = \
	$(gtk_filepublisherdoc_DATA) \
	intltool-extract.in \
	intltool-merge.in \
	intltool-update.in\
	$(NULL)

DISTCLEANFILES = \
	intltool-extract \
	intltool-merge \
	intltool-update \
	po/.intltool-merge-cache \
	$(NULL)

