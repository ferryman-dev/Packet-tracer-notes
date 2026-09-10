###CLI navigation


- enable
- disable
- configure terminal (conf t)
- exit
- end
- ?
- do (allows you to run privileged EXEC-mode commands from inside a configuration mode without having to exit it)

###Basic configuration commands

- hostname R1
- no ip domain-lookup (this disables DNS lookup if you make a typo, so the ClI dosent just freeze)
- enable secret <password>
- banner motd #<message># (sets a message displayed when the device is accessed)
