		what commands do
1.ifconfig
	the command is mostly not on powershell because you need to download net-tools
uses: to get network interface information
2.ip
	you can use "ip a" or "ip addr"
uses; same as ifconfig
3.traceroute
	you can use it to follow the ip addresses and the time it, used withh the connand then a website address, traceart is for windows systems
uses: follow the path that the command takes
4.tracepath
	first you have to do "sudo apt-get install inetutils-traceroute" after do the same as the traceroute command
uses: the same as traceroute but has the round trip information, it aslo hops to the destination
5.ping
	do ping "website.com"
uses: meassure the time that it takes for a round trip of a message,it sends ICMP(Imternet Control Message Protocol)
6.netstat
	do netstat -tuln( to display listening ports),netstat -an(to display all sockets),netstat -s(to display statistics for each protocol
7.ss
	same as netstat but just explained differently
uses: a little simpler, easier to get info that you want
8.dig
	powerful tools for querying the DNS( Domain system name)
uses: dig "website.com, you can also add @dns-sever-ip for a specific server,or NX for mail servers, and do dig -x 8.8.8.8 for a reverse DNS lookup

9.nslookup
	its for finding out the domain name,mostly used to troubleshoot and dig is mostly used amd more flexible
uses: nslookup "example.com",nslookup "example".com dns-server-ip, and nslookup 8.8.8.8 for reverse lookup
10.route
	it is used to display and manipulate and display routing tables
uses:route -n shows routing table,sudo route add -net destination-network netmask netmask-address gateway-ip shows"adds routing table

host: The host command is used for DNS lookups. It can be used to find the IP address associated with a domain name or vice versa.


host example.com
arp: The arp command is used to display and manipulate the Address Resolution Protocol (ARP) cache. It shows the mapping of IP addresses to MAC addresses on a local network.


arp -a
iwconfig: The iwconfig command is used to configure and display information about wireless network interfaces. It provides details such as signal strength, encryption, and mode.


iwconfig
hostname: The hostname command is used to display or set the hostname of a system. It can be helpful for identifying the system in a network.


hostname
curl or wget: Both curl and wget are used for downloading files from the internet. They support various protocols, and you can use them to retrieve content from web servers.


curl https://example.com/file.txt


















































[GameNr "82658147"]
[TimeControl "10+0"]
[Variant "FFA"]
[RuleVariants "Blindfold EnPassant Play4Mate"]
[StartFen4 "2PC"]
[White "NotGoodAtGame09"]
[WhiteElo "1500"]
[Black "NotTakenUsername2444"]
[BlackElo "1500"]
[Result "1-0"]
[Termination "Checkmate • 1-0"]
[Site "www.chess.com/variants/blindfold/game/82658147"]
[Date "Wed May 14 2025 16:32:55 GMT+0000 (Coordinated Universal Time)"]
[CurrentMove "43"]

1. g5-g7 .. g10-g8
2. Bf4-i7 .. Ne11-f9
3. h5-h6 .. h10-h8
4. g7xh8 .. Nf9-g7
5. h6xNg7 .. Qg11-h10
6. Nj4-h5 .. Nj11-i9
7. Nh5-j6 .. Qh10-g10
8. h8xNi9 .. j10xi9
9. Bi4-g6 .. Bi11-f8
10. g7xBf8 .. Qg10-d7
11. e5-e6 .. Qd7xBi7
12. O-O .. Qi7-k9
13. Qg4-i6 .. O-O
14. Nj6-k8 .. Qk9xNk8
15. Qi6xQk8 .. Kj11-j10
16. Qk8-j7+ .. Kj10-k9
17. Qj7-i7+ .. Kk9-k8
18. j5-j7+ .. Kk8-k7
19. Qi7-j6+ .. Kk7-j8
20. i5-i7+ .. Kj8-k9
21. Qj6-k6+ .. Kk9-j10
22. Qk6xk10+#

wget https://example.com/file.txt
mtr: The mtr command (My Traceroute) is a network diagnostic tool that combines the functionality of ping and traceroute. It continuously traces the route to a destination and provides statistics on packet loss and latency.


mtr example.com
whois: The whois command is used to query the WHOIS database, providing information about domain registrations, owners, and other details.


whois example.com
ifplugstatus: The ifplugstatus command checks the status of a network interface's link and prints whether a cable is plugged in or not.


ifplugstatus eth0
iftop: The iftop command is a real-time console-based network bandwidth monitoring tool. It shows a list of network connections and their corresponding data rates.


iftop
tcpdump: The tcpdump command is a packet analyzer that allows the user to display, capture, and analyze TCP, UDP, and other packets on a network.


sudo tcpdump -i eth0
These commands are valuable for network troubleshooting, diagnostics, and general information retrieval in a Linux environment.


Alias           ? -> Where-Object                                             
Alias           % -> ForEach-Object                                           
Alias           cd -> Set-Location                                            
Alias           chdir -> Set-Location                                         
Alias           clc -> Clear-Content                                          
Alias           clhy -> Clear-History                                         
Alias           cli -> Clear-Item                                             
Alias           clp -> Clear-ItemProperty                                     
Alias           cls -> Clear-Host                                             
Alias           clv -> Clear-Variable                                         
Alias           copy -> Copy-Item                                             
Alias           cpi -> Copy-Item                                              
Alias           cvpa -> Convert-Path                                          
Alias           dbp -> Disable-PSBreakpoint                                   
Alias           del -> Remove-Item                                            
Alias           dir -> Get-ChildItem                                          
Alias           ebp -> Enable-PSBreakpoint                                    
Alias           echo -> Write-Output                                          
Alias           epal -> Export-Alias                                          
Alias           epcsv -> Export-Csv                                           
Alias           erase -> Remove-Item                                          
Alias           etsn -> Enter-PSSession                                       
Alias           exsn -> Exit-PSSession                                        
Alias           fc -> Format-Custom                                           
Alias           fhx -> Format-Hex                                  7.0.0.0    M
Alias           fl -> Format-List                                             
Alias           foreach -> ForEach-Object                                     
Alias           ft -> Format-Table                                            
Alias           fw -> Format-Wide                                             
Alias           gal -> Get-Alias                                              
Alias           gbp -> Get-PSBreakpoint                                       
Alias           gc -> Get-Content                                             
Alias           gci -> Get-ChildItem                                          
Alias           gcm -> Get-Command                                            
Alias           gcs -> Get-PSCallStack                                        
Alias           gdr -> Get-PSDrive                                            
Alias           gerr -> Get-Error                                             
Alias           ghy -> Get-History                                            
Alias           gi -> Get-Item                                                
Alias           gjb -> Get-Job                                                
Alias           gl -> Get-Location                                            
Alias           gm -> Get-Member                                              
Alias           gmo -> Get-Module                                             
Alias           gp -> Get-ItemProperty                                        
Alias           gps -> Get-Process                                            
Alias           gpv -> Get-ItemPropertyValue                                  
Alias           group -> Group-Object                                         
Alias           gsn -> Get-PSSession                                          
Alias           gu -> Get-Unique                                              
Alias           gv -> Get-Variable                                            
Alias           h -> Get-History                                              
Alias           history -> Get-History                                        
Alias           icm -> Invoke-Command                                         
Alias           iex -> Invoke-Expression                                      
Alias           ihy -> Invoke-History                                         
Alias           ii -> Invoke-Item                                             
Alias           ipal -> Import-Alias                                          
Alias           ipcsv -> Import-Csv                                           
Alias           ipmo -> Import-Module                                         
Alias           irm -> Invoke-RestMethod                                      
Alias           iwr -> Invoke-WebRequest                                      
Alias           md -> mkdir                                                   
Alias           measure -> Measure-Object                                     
Alias           mi -> Move-Item                                               
Alias           move -> Move-Item                                             
Alias           mp -> Move-ItemProperty                                       
Alias           nal -> New-Alias                                              
Alias           ndr -> New-PSDrive                                            
Alias           ni -> New-Item                                                
Alias           nmo -> New-Module                                             
Alias           nsn -> New-PSSession                                          
Alias           nv -> New-Variable                                            
Alias           oh -> Out-Host                                                
Alias           popd -> Pop-Location                                          
Alias           pushd -> Push-Location                                        
Alias           pwd -> Get-Location                                           
Alias           r -> Invoke-History                                           
Alias           rbp -> Remove-PSBreakpoint                                    
Alias           rcjb -> Receive-Job                                           
Alias           rcsn -> Receive-PSSession                                     
Alias           rd -> Remove-Item                                             
Alias           rdr -> Remove-PSDrive                                         
Alias           ren -> Rename-Item                                            
Alias           ri -> Remove-Item                                             
Alias           rjb -> Remove-Job                                             
Alias           rmo -> Remove-Module                                          
Alias           rni -> Rename-Item                                            
Alias           rnp -> Rename-ItemProperty                                    
Alias           rp -> Remove-ItemProperty                                     
Alias           rsn -> Remove-PSSession                                       
Alias           rv -> Remove-Variable                                         
Alias           rvpa -> Resolve-Path                                          
Alias           sajb -> Start-Job                                             
Alias           sal -> Set-Alias                                              
Alias           saps -> Start-Process                                         
Alias           sbp -> Set-PSBreakpoint                                       
Alias           select -> Select-Object                                       
Alias           set -> Set-Variable                                           
Alias           si -> Set-Item                                                
Alias           sl -> Set-Location                                            
Alias           sls -> Select-String                                          
Alias           sp -> Set-ItemProperty                                        
Alias           spjb -> Stop-Job                                              
Alias           spps -> Stop-Process                                          
Alias           sv -> Set-Variable                                            
Alias           type -> Get-Content                                           
Alias           where -> Where-Object                                         
Alias           wjb -> Wait-Job 


IP address (IPv4):

It's like a unique number for your computer on a network, written as sets of numbers (e.g., 192.168.0.1).

Subnet Masks:
A tool that helps computers understand which part of an IP address is for the network and which is for the specific device.

Gateway:
Think of it as the traffic cop between your home network and the internet, helping data travel back and forth.

DNS (Domain Name System):
It's like a phone book for the internet, translating easy-to-remember names (like www.example.com) into computer-friendly IP addresses.

Network Switch:
A smart traffic director for devices within your home or office, making sure data gets to the right place efficiently.

Network Router:
Connects different networks (like your home network and the internet), directing data between them.

Access Points:
Devices that make it possible for your phone or laptop to connect to the internet wirelessly, like Wi-Fi hubs.

MAC address:
A unique ID for each device's internet connection, like a fingerprint for your computer or phone.

Ports in Network Addressing:
Doorways on your computer that different services use to communicate with the outside world, each labeled with a specific number.

Types of Networks:
WAN (Wide Area Network): Big networks covering large areas.
LAN (Local Area Network): Small networks, like in your home or office.
PAN (Personal Area Network): Personal device connections, like Bluetooth.
MAN (Metropolitan Area Network): City-wide networks.
VPN (Virtual Private Network): Secure internet connections, useful for working remotely.

git hub commands


to install github on the terminal.




