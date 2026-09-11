## Assigning IP addresses

```cisco
 interface gigabitethernet0/0/0
 ip address <IP> <subnet mask>
 no shutdown
``` 
## Default gateway

- ip default-gateway <IP>

## Verification

- show ip interface brief
- show interfaces
- ping <IP>

### Example router configuration

- enable
- conf t
- interface gigabitethernet0/0/0
- ip address 192.168.1.1 255.255.255.0
- no shutdown
