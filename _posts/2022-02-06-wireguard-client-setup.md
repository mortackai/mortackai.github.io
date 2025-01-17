---
layout: post
title: Wireguard Client Setup
date: 2022-02-06
---

install prerequisites

> `sudo apt install resolvconf curl`

install wireguard

> `sudo apt install wireguard wg-quick`

mv .conf file to /etc/wireguard/
start vpn

> `wg-quick up file.conf`
