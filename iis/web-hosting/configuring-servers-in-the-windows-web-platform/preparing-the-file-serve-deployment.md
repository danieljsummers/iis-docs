---
title: "Separate Partitions for Improved Performance | Microsoft Docs"
author: walterov
description: "On the file server, performance may be improved by separating the system and content partitions and physical hard drives. Setup The following setup is recomm..."
ms.author: iiscontent
manager: soshir
ms.date: 12/01/2007
ms.topic: article
ms.assetid: e1de6e2a-3c68-4bdf-a78d-19f4020c23a8
ms.technology: iis-hosting
ms.prod: iis
msc.legacyurl: /learn/web-hosting/configuring-servers-in-the-windows-web-platform/preparing-the-file-serve-deployment
msc.type: authoredcontent
---
Separate Partitions for Improved Performance
====================
by [Walter Oliver](https://github.com/walterov)

## Introduction

On the file server, performance may be improved by separating the system and content partitions and physical hard drives.

## Setup

The following setup is recommended:

- Use a unique partition and physical drive(s) for the system.
- Use a separate partition and physical drive(s) for the content.