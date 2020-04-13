---
description: Personal notes by Larry Lauer
---

# Hacking for fun and profit

## Pentesting Notes

Initial host scan a couple of options

```
$ nmap -T4 -A -p- host
$ nmap -sC -sV -oA nmap/initial host
$ nmap --script=vuln host
```

{% hint style="info" %}
 Super-powers are granted randomly so please submit an issue if you're not happy with yours.
{% endhint %}

Once you're strong enough, save the world:

{% code title="hello.sh" %}
```bash
# Ain't no code for that yet, sorry
echo 'You got to trust me on this, I saved the world'
```
{% endcode %}



