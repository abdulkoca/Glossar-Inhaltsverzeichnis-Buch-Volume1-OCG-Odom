# Glossar-Inhaltsverzeichnis-Buch-Volume1-OCG-Odom


Buch Volume 1:

ISL VLAN: 
Inter-Switch Link (ISL) ist ein Cisco-proprietäres Trunking-Protokoll für VLAN-Traffic über Switch-Links. Es kapselt Frames vollständig und wurde durch den Standard 802.1Q ersetzt.

STP: 
Spanning Tree Protocol (802.1D) verhindert Loops in Ethernet-Netzen durch Root-Bridge-Wahl und Port-Blocking. Konvergenz dauert bis zu 50 Sekunden.

RSTP: 
Rapid Spanning Tree Protocol (802.1w) verbessert STP mit schneller Konvergenz (unter 10s) über direkte Link-Übergänge. Kompatibel mit STP.

BPQU: 
BPDU Guard (Bridge Protocol Data Unit Guard) deaktiviert Ports sofort bei unerwarteten STP-BPDUs. Schützt vor Rogue-Switches auf Access-Ports.

EtherChannel: 
Bundelt 2-8 physische Links zu einem logischen Kanal für Redundanz und höhere Bandbreite. Verhandelt via LACP (Standard) oder PAgP (Cisco).

SVI: 
Switched Virtual Interface (z.B. „interface vlan 10“) ist eine virtuelle L3-Schnittstelle für Inter-VLAN-Routing auf Layer-3-Switches. Erhält IP pro VLAN.

SLAAC: 
Stateless Address Autoconfiguration vergibt IPv6-Adressen automatisch via Router Advertisements. Host kombiniert Netzwerkprefix mit eigener Interface-ID (EUI-64).
