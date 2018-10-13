# auditd-rules

An auditd ruleset for monitoring linux servers.

Derived from a gist published by Florian Roth at https://gist.github.com/Neo23x0/9fe88c0c5979e017a389b90fd19ddfee.

Linux Man Pages: auditd.conf (5)  https://www.systutorials.com/docs/linux/man/5-auditd.conf/

## Usage
```
apt install -y auditd
cp audit.rules /etc/audit/rules.d/audit.rules
service auditd restart
```
