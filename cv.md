# Vadim Shut

## Сontact Info

- **email:** vadimshut1992@gmail.com
- **Telegram:** Vadim
- **Discord:** Vadim(@vadimshut)

## Summary

My main goal is to get a job as a front-end developer. I want to work in IT-company and to become a high-level developer. I am ready to spend all my free time on improving programming skills.

## Skills

- HTML5
- CSS3
- Git
- JavaScript
- Python
- Cisco: swithing and routing, security.
- Windows: AD, DNS, DHCP.
- WAF: managing, support, tuning web application protection rules
- Sandbox: managing, support, tuning (Cuckoo, Checkpoint, Lastline)
- SIEM: introduction, creating reports, dashboards, rules. (Wazuh and other)
- Firewall/NGFirewall: Pfsense, OPNsense NGFirewall

## Code examples

```JavaScript
myWeather.on('click', () => {
    navigator.geolocation.getCurrentPosition(function({coords}){
        getWeather(coords.latitude, coords.longitude)
})});
```

```Python
def get_arguments():
    parser = argparse.ArgumentParser()
    parser.add_argument("-t", "--target", dest="target_ip", help="IP for: 192.168.1.1")
    parser.add_argument("-g", "--gateway", dest="gateway_ip", help="IP : 192.168.2.1")
    options = parser.parse_args()
    if not options.target_ip:
        parser.error(Fore.RED + "[-]" + Fore.GREEN + "Please specify the target IP, use --help for more info.")
    if not options.gateway_ip:
        parser.error(Fore.RED + "[-]" + Fore.GREEN + "Please specify the gateway IP, use --help for more info.")

    return options.target_ip, options.gateway_ip

```

```Python
def packet_analysis(packet):
    if packet.haslayer(http.HTTPRequest):
        url = geturl(packet)
        get_time_now()
        print(f"[+] HTTP Request >> {url.decode()}")
        login_info = get_login_info(packet)
        if login_info:
            get_time_now()
            print(Fore.YELLOW + f"[+] Possible username/password {login_info}")
```

## Experience

- https://github.com/vadimshut/OTX_connector
- https://github.com/vadimshut/Network-Scanner
- https://github.com/vadimshut/ARP-spoofer
- https://github.com/vadimshut/Packet-sniffer
- https://github.com/vadimshut/DNS-spoofer
