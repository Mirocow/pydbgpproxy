# pydbgpproxy

## Install

* cd /opt
* mkdir pydbgpproxy
* cd pydbgpproxy
* wget https://github.com/Mirocow/pydbgpproxy/archive/master.zip ./
* unzip master.zip ./
* ln -s $(pwd)/pydbgpproxy /usr/local/bin/pydbgpproxy

## Errors

if you have such mistake

```
Traceback (most recent call last):
  File "/usr/local/bin/pydbgpproxy", line 106, in <module>
    import dbgp.serverBase
ImportError: No module named dbgp.serverBase
```

you can fixed it

``` sh
echo "export PYTHONPATH=\${PYTHONPATH}:/opt/bin/pydbgpproxy/pythonlib" » ~/.bashrc
```
