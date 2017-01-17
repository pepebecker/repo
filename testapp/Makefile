include $(THEOS)/makefiles/common.mk

APPLICATION_NAME = TestApp
TestApp_FILES = main.m PBAppDelegate.m PBRootViewController.m
TestApp_FRAMEWORKS = UIKit CoreGraphics

include $(THEOS_MAKE_PATH)/application.mk

after-install::
	install.exec "killall \"TestApp\"" || true
