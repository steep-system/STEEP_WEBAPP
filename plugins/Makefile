SUBDIRS = contactfax desktopnotifications filepreviewer folderwidgets gmaps intranet passwd pimfolder quickitems safesenderssettings titlecounter webappmanual zdeveloper

.PHONY: subdirs $(SUBDIRS)

subdirs: $(SUBDIRS)

$(SUBDIRS):
	$(MAKE) DESTDIR=../../deploy/plugins/$@ -C $@

all: subdirs

clean:
