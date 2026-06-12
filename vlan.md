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

<div class="command-row" markdown="1">

<div class="command-box" markdown="1">

## Opret VLAN 10 & VLAN 20

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

</div>

<div class="info-box" markdown="1">

### Klar til at konfigurere?

Kopiér kommandoerne og indsæt dem på dit udstyr.

</div>

</div>

## Kontroller VLAN-konfigurationen

```cisco
show vlan brief
```

## Giv VLAN'et adgang til et interface

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
<div class="command-row" markdown="1">

<div class="command-box" markdown="1">
## Verificering

```cisco
show vlan brief
```
<div class="info-box" markdown="1">

### Klar til verificering??

Kopiér kommandoerne og indsæt dem på dit udstyr.

</div>

</div>

## Video-guide

📽️ Video kommer snart

</div>
