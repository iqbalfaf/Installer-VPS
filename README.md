# Script Auto Installer SSH Debian, Ubuntu
Script auto install vps Debian,Ubuntu.
Script ini hanya jalan di OS Debian dan Ubuntu KVM

# Cara Install Script 
<code>
wget https://raw.githubusercontent.com/iqbalfaf/Installer-VPS/master/setup.sh && chmod +x setup.sh && ./setup.sh
</code>

# Fitur Script Auto Install
Service : 
--------- 
OpenSSH (22) <br>
Dropbear (443, 143,109,110) <br>
SSL(443) <br>
Squid3(80, 8000, 3128 "limit to IP IPVPS") <br>
badvpn(badvpn-udpgw port 7300) <br>
 
Tools : 
------- 
htop, rkhunter, nethogs: nethogs 
 
Script : 
-------- 
menu (Menu di dalam script)
  - Buat Akun SSH/OpenVPN (kuy-add) 
  - Generate Akun SSH/OpenVPN (kuy-gen) 
  - Monitoring Dropbear (dropmon [PORT]) 
  - Cek Login Dropbear, OpenSSH, (kuy-login) 
  - Kill Multi Login Manual (1-2 Login) (kuy-limit [x]) 
  - Daftar Akun dan Expire Date (kuy-list) 
  - Speedtest (speedtest) 
  - Benchmark (benchmark) 
  - Reboot Server 
 
Fitur lain : 
------------ 
Webmin         : http://IPVPS:10000/ 
Timezone       : Asia/Jakarta (GMT +7) 
IPv6           : [off] 
Auto Lock kuy Expire tiap jam 00:00 
Auto Reboot tiap jam 00:00 dan jam 12:00 
