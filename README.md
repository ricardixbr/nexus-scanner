# Nexus scanner

Static Telegram Mini App that reads QR codes with Telegram's native scanner
and returns the raw text to the bot that opened it, through
`Telegram.WebApp.sendData`, as `{"v": 1, "codes": [...]}`.

It stores nothing, calls no server and holds no per-instance data, so any
bot can use this hosted copy. Published from `webapp/scanner` of the Nexus
project; see its ADR-0006.

Served at https://ricardixbr.github.io/nexus-scanner/
