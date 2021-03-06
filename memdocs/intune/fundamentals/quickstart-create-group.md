---
title: 'Inicio rápido: Crear un grupo para administrar usuarios'
titleSuffix: Microsoft Intune
description: En este inicio rápido, usará Microsoft Intune para crear un grupo basado en usuarios existentes.
keywords: ''
author: Erikre
ms.author: erikre
manager: dougeby
ms.date: 01/17/2020
ms.topic: quickstart
ms.service: microsoft-intune
ms.subservice: fundamentals
ms.localizationpriority: high
ms.technology: ''
ms.assetid: 723f4b4e-3090-4811-84ff-6af652abea5a
ms.reviewer: ''
ms.suite: ems
search.appverid: MET150
ms.custom: intune-azure
ms.collection: M365-identity-device-management
ms.openlocfilehash: d7adb23f4709bf3ead07a01cb00d1b38fcb23c40
ms.sourcegitcommit: 7f17d6eb9dd41b031a6af4148863d2ffc4f49551
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/21/2020
ms.locfileid: "79356913"
---
# <a name="quickstart-create-a-group-to-manage-users"></a>Inicio rápido: Crear un grupo para administrar usuarios

En este inicio rápido, usará Intune para crear un grupo basado en un usuario existente. Los grupos se usan para administrar los usuarios y controlar el acceso de los empleados a los recursos de la empresa. Estos recursos pueden formar parte de la intranet de la empresa o ser recursos externos, como sitios de SharePoint, aplicaciones de SaaS o aplicaciones web.

Si no tiene una suscripción a Intune, [regístrese para obtener una cuenta de prueba gratuita](free-trial-sign-up.md).

>[!NOTE]
>Intune ofrece los grupos creados previamente **Todos los usuarios** y **Todos los dispositivos** en la consola con las optimizaciones integradas para su comodidad.

## <a name="prerequisites"></a>Requisitos previos

- Suscripción a Microsoft Intune: [regístrese para obtener una cuenta de prueba gratuita](../fundamentals/free-trial-sign-up.md).
- Para completar este inicio rápido, debe [crear un usuario](quickstart-create-user.md).

## <a name="sign-in-to-intune-in-the-microsoft-endpoint-manager"></a>Inicio de sesión en Intune en Microsoft Endpoint Manager

Inicie sesión en el [Centro de administración de Microsoft Endpoint Manager](https://go.microsoft.com/fwlink/?linkid=2109431) como [administrador global o administrador de servicios de Intune](users-add.md#types-of-administrators). Si ha creado una suscripción de prueba de Intune, la cuenta con la que creó la suscripción es el administrador global.

## <a name="create-a-group"></a>Crear un grupo

Creará un grupo que se usará más adelante en esta serie de inicio rápido. Para crear un grupo:

1. Una vez que abra **Microsoft Endpoint Manager**, seleccione **Grupos** > **Nuevo grupo**.
2. En el cuadro desplegable **Tipo de grupo**, seleccione **Seguridad**.
3. En el campo **Nombre del grupo**, escriba el nombre del grupo nuevo (por ejemplo, **Contoso Testers** [Evaluadores de Contoso]).
4. Agregue una **descripción del grupo** para el grupo.
5. Establezca **Tipo de miembro** en **Asignado**. 
6. En **Miembros**, seleccione el vínculo y agregue uno o más miembros para el grupo de la lista.

    ![Captura de pantalla de creación de un grupo en Microsoft Intune](./media/quickstart-create-group/quickstart-use-groups-01.png)

7. Haga clic en **Seleccionar** > **Crear**.

Cuando haya creado correctamente el grupo, aparecerá en la lista **Todos los grupos**. 

## <a name="next-steps"></a>Pasos siguientes

En este inicio rápido, usó Intune para crear un grupo basado en un usuario existente. Para obtener más información sobre cómo agregar grupos a Intune, consulte [Agregar grupos para organizar usuarios y dispositivos](groups-add.md).

Para seguir esta serie de tutoriales de inicio rápido de Intune, pase al siguiente tutorial de inicio rápido.

> [!div class="nextstepaction"]
> [Inicio rápido: Configurar la inscripción automática para dispositivos Windows 10](../enrollment/quickstart-setup-auto-enrollment.md)
