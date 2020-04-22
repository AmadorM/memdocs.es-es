---
author: aczechowski
ms.author: aaroncz
ms.prod: configuration-manager
ms.technology: configmgr-core
ms.topic: include
ms.date: 02/03/2020
ms.openlocfilehash: 0db30a8fdc96bc1e1d2d1ff2a059eca8d454d48e
ms.sourcegitcommit: bbf820c35414bf2cba356f30fe047c1a34c5384d
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/21/2020
ms.locfileid: "81692103"
---
### <a name="cant-create-or-edit-some-collections"></a><a name="ki_coll"></a> No se pueden crear o editar algunas colecciones

<!--6197183-->
En esta versión de la rama Technical Preview no se pueden crear colecciones. Además, tampoco se pueden editar las propiedades de una colección de usuario.

Para buscar una solución alternativa a este problema, use los cmdlets de PowerShell de Configuration Manager para crear colecciones y editar las colecciones de usuario existentes. Algunos de los cmdlets disponibles para administrar colecciones son los siguientes:

- [New-CMCollection](https://docs.microsoft.com/powershell/module/configurationmanager/new-cmcollection?view=sccm-ps)

- [Get-CMCollection](https://docs.microsoft.com/powershell/module/configurationmanager/get-cmcollection?view=sccm-ps)

- [Set-CMCollection](https://docs.microsoft.com/powershell/module/configurationmanager/set-cmcollection?view=sccm-ps#related-links)

- [Add-CMCollectionMembershipRule](https://docs.microsoft.com/powershell/module/configurationmanager/add-cmcollectionmembershiprule?view=sccm-ps)
