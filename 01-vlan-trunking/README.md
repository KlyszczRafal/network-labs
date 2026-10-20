# Lab 01 – VLAN i router-on-a-stick

## Cel
Podzia³ sieci na VLAN 10 (Biuro) i VLAN 20 (Magazyn) z routingiem miêdzy nimi.

## Topologia
![Topologia](topology.png)

## Adresacja
| Urz¹dzenie | Interfejs | Adres IP | VLAN |
|---|---|---|---|
| R1 | G0/0.10 | 192.168.10.1/24 | 10 |
| R1 | G0/0.20 | 192.168.20.1/24 | 20 |
| PC1 | NIC | 192.168.10.10/24 | 10 |

## Kluczowa konfiguracja
(najwa¿niejsze fragmenty z configs/, np. subinterfejsy i trunk)

## Weryfikacja
- `show vlan brief`
- `show interfaces trunk`
- ping z PC1 (VLAN 10) do PC3 (VLAN 20) – dzia³a

## Czego siê nauczy³em
2–3 zdania w³asnymi s³owami, np. jaki b³¹d pope³ni³eœ i jak go znalaz³eœ.