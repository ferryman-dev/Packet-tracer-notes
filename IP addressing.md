## Assigning IP addresses

```cisco
 interface gigabitethernet0/0/0
 ip address <IP> <subnet mask>
 no shutdown
``` 
## Default gateway
```cisco
ip default-gateway <IP>
```
## Verification
```cisco
show ip interface brief
show interfaces
 ping <IP>
```
### Example router configuration
```cisco
 enable
 conf t
interface gigabitethernet0/0/0
ip address 192.168.1.1 255.255.255.0
no shutdown
```
