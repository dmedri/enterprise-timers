install:
	sudo cp -a *.timer *.target *.target.wants /etc/systemd/system/ && \
	sudo chmod 700 enterprise-timers && \
	sudo chown root.root enterprise-timers && \
	sudo cp enterprise-timers /usr/bin;

enable:
	sudo enterprise-timers enable;
start:
	sudo enterprise-timers start;
