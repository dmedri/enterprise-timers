USRDIR = ~/.config/systemd/user/
SYSDIR = /etc/systemd/system/

install:
	mkdir -p $(USRDIR)
	cp -a *.{timer,target,target.wants} $(USRDIR)
	chmod u+x enterprise-timers-user

install_system:
	sudo cp -a *.{timer,target,target.wants} $(SYSDIR)
	chmod u+x enterprise-timers-system
