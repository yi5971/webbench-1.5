# webbench-1.5
1. support post method from `-P [postdata]`
```
./webbench -c 10 -t 30 -P "username=peter&&clients=3.5.11&&policy=%E7%A9%BA%E7%AD%96%E7%95%A5" http://192.168.10.11/heartbeat.php
```

2. support post method from `-F [filename]` 
```
./webbench -c 10 -t 30 -F "postdata.txt" http://192.168.10.11/heartbeat.php
```
postdata.txt
```
username=peter&&clients=3.5.11&&policy=%E7%A9%BA%E7%AD%96%E7%95%A5
username=lily&&clients=3.5.11&&policy=%E7%A9%BA%E7%AD%96%E7%95%A5
username=sam&&clients=3.5.11&&policy=%E7%A9%BA%E7%AD%96%E7%95%A5
```


#### TODO

urlencode postdata
