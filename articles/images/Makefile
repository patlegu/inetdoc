ifndef $(MAIN_DIR)
MAIN_DIR = $(HOME)/inetdoc
endif

# Type(s) de traitement
PROCESS = symlink

SYMLINKS = \
        $(MAIN_DIR)/images/thumbs/thumb*.png \
        $(MAIN_DIR)/articles/modelisation/images/modelisation-osi.{png,svg} \
        $(MAIN_DIR)/articles/inter-vlan-routing/images/ieee8021q-frame.{png,svg} \
        $(MAIN_DIR)/articles/inter-vlan-routing-openvswitch/images/ovs-image.jpg

all: $(PROCESS)

include $(MAIN_DIR)/common/Makefile.Rules
