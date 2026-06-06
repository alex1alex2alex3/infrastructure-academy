---
layout: page
title: VLAN
parent: Netværk
---

<div style="background:#001a00;
            border:2px solid #00ff00;
            color:#00ff00;
            padding:15px;
            border-radius:8px;
            margin-bottom:20px;
            box-shadow:0 0 10px #00ff00;
            max-width:1500px;
            width:100%;">

🚧 <strong>Under opbygning</strong><br>
Alis Netværk Akademi er stadig under udvikling.
Nyt indhold, labs og dokumentation tilføjes løbende.

</div>

<div class="vlan-page" markdown="1">            
# VLAN (Virtual Local Area Network)

## Opret Vlan 10 & vlan 20
```cisco
enable
configure terminal
vlan 10
 name skrivnavnher
 exit

vlan 20
 name skrivnavnher
 exit
```
## Kontroller VLAN-konfigurationen
```cisco
show vlan brief
```
## Giv vlan´et adgang til et interface
Følgende konfiguration placerer FastEthernet0/1 i VLAN 10 og FastEthernet0/2 i VLAN 20.
```cisco
interface FastEthernet0/1
 switchport access vlan 10
 switchport mode access
 exit

interface FastEthernet0/2
 switchport access vlan 20
 switchport mode access
 end
```
## Verificering
```cisco
show vlan brief
```

## Video-guide

📽️ Video Kommer snart

</div>
