# systemctl Cheat Sheet
| If you are using systemd, you should know some commands about systemctl.

Status of a unit

```
systemctl status <unit>
```

Control units

```
systemctl [start|stop|reload|restart] <unit>
```

List units

```
systemctl list-units [--all]
```

List unit files

```
systemctl list-unit-files
```

Show Content of a unit file

```
systemctl cat httpd.service
```

Get / set default runlevel

```
systemctl [get-default|set-default <target>]
```

Reach a target

```
systemctl isolate <target>
```