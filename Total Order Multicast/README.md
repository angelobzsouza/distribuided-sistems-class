# Total Order Multicast Algorithm

This code simulate a total order multicast algorithm. Basically, one process send a message in multicast and all conected process receive it. When one process receive a message, it send one answer ack to sender. When all message's acks are receive, the process send the message to the application.

## Running
1. Open four different terminals
2. Run the application in each one with the following commands

```
python totalOrderMulticast.py 9000 0
```
```
python totalOrderMulticast.py 9001 1
```
```
python totalOrderMulticast.py 9002 2
```
```
python totalOrderMulticast.py 9003 3
```

3. Type a string in one of process and see the magic.