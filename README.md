# pydbgpproxy

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
