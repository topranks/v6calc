# v6calc
Very simple IPv6 "equivalent" of the old ipcalc command-line tool

I just made this one day annoyed that 'ipcalc' doesn't support IPv6.

Requires the 'num2word' library installed.  On Debian/Ubuntu:

    sudo apt install python3-num2words

Elsewhere:

    pip3 install num2words


Example:
```
root@host:~$ v6calc 240e:978:305:4:50::2/55
Address:    240e:978:305:4:50::2/55
Network:    240e:978:305::/55
Broadcast:  240e:978:305:1ff:ffff:ffff:ffff:ffff
Num Addrs:  Over nine sextillion (9,444,732,965,739,290,427,392)
Num /64:    512
Num /60:    32
Num /56:    2
```

