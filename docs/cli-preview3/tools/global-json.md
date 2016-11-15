---
title: global.json reference | .NET Core
description: global.json reference
keywords: .NET, .NET Core
author: aL3891
ms.author: mairaw
manager: wpickett
ms.date: 11/02/2016
ms.topic: article
ms.prod: .net-core
ms.technology: .net-core-technologies
ms.devlang: dotnet
ms.assetid: 3f6d6421-c457-493c-9fec-f3d5cac541b3
---

# global.json reference

The global.json file is still present in the .NET Core Command Line Preview 3. However, its main purpose is not to define 
solution metadata as in previous releases, but to allow selection of the CLI version being used through the `sdk` property. 

This reference reflects the above fact. 

## sdk
Type: Object

Specifies information about the SDK.

### version
Type: String

The version of the SDK to use.

For example:

```json
{
    "sdk": {
        "version": "1.0.0-preview2-003121"
    }
}
```
