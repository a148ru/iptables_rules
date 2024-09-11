правила iptables 
нужен пакет iptables-persistent

сохранить 

```shell
# iptables-save > /etc/iptables/rules.v4
# ip6tables-save > /etc/iptables/rules.v6
```

востановить

```shell
# iptables-restore < file_rules.v4
# ip6tables-restore < file_rules.v6
```

