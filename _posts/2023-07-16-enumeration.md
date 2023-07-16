---
layout: post
author: r35e7
---

Enumeración de puertos abiertos con nmap.

```bash
nmap -sS -n -Pn --open -p- -vvv --min-rate 5000 -oG ports targetip
```
Extraemos los puertos de el archivo grepeable "ports".
```bash
extractPorts ports
```
Enumeracion de servicios y scripts basicos de nmap.
```bash
nmap -sCV -pPUERTOS -Pn -n -oN target **targetip**
```
{{Esto es un comentario}}
