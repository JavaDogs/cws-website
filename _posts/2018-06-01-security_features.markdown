---
layout: default
img: javadog.png
category: Features
title: Security Features
description: |
---
CWS is written purely in Java 8 / Java EE 7. It is thus only relying on the
very solid Java Server components, which is frequently seeing security updates.
By not relying on anything else, the security problems have been minimized.

All data stored in CWS is encrypted using a combination of a MasterKey and a
CircleKey. Both of these are AES based Symmetric keys, and CircleKeys are
protected using a RSA based Asymmetric key. The entire setup is build around the
notion that control of keys and data belongs to the owners.

This also means that CWS is the perfect companion for anyone requiring a secure
storage to be GDPR compliant.
