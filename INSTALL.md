enterprise-timers
=================

Install
-------

There are two way to install this timers:

- at system level (under ``/etc/systemd/`` directory, as root);
- at user level (under your own ``~/.config/systemd/user/`` directory).

The last option come up in recent systemd releases. This is why out first deployment was targeted for system level, and now for users as default. The following install commands are for user. For system location, use ``make install_system``.

```
cd timers
make install
```

In the same directory, run:

```
./enterprise-timers-user enable
./enterprise-timers-user start
```
to enable and start services.

To disable and stop:
```
./enterprise-timers-user stop
./enterprise-timers-user disable
```
