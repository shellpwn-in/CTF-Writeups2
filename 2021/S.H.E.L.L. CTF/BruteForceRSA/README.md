Question: Flag Format : shellctf{}
files: script.py, values.json
1) from values.json
<pre>e = 65537
n = 105340920728399121621249827556031721254229602066119262228636988097856120194803
enc_msg = 36189757403806675821644824080265645760864433613971142663156046962681317223254
</pre>

2) use [RsaCtfTool](https://github.com/Ganapati/RsaCtfTool)
3) `python3 RsaCtfTool.py -n 105340920728399121621249827556031721254229602066119262228636988097856120194803 -e 65537 --uncipher 36189757403806675821644824080265645760864433613971142663156046962681317223254`