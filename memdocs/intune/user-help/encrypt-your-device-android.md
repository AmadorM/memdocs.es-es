---
title: Cifrado de un dispositivo Android en Intune | Microsoft Docs
description: Pasos para activar el cifrado de dispositivos Android cuando Intune lo requiera.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 04/19/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.subservice: end-user
ms.technology: ''
ms.assetid: d4430e92-04cc-48e9-a77a-81b95a90b6b3
searchScope:
- User help
ROBOTS: ''
ms.reviewer: arnab
ms.suite: ems
ms.custom: intune-enduser
ms.collection: ''
ms.openlocfilehash: ee2d220e308b406251f049e1c17422f89ee36534
ms.sourcegitcommit: 3d895be2844bda2177c2c85dc2f09612a1be5490
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 03/13/2020
ms.locfileid: "79348788"
---
# <a name="encrypting-your-android-device"></a>Cifrado del dispositivo Android

El cifrado de dispositivos protege los archivos y las carpetas de accesos no autorizado si el dispositivo se pierde o se sustrae. Después de activar el cifrado del dispositivo, solo los usuarios que tengan la contraseña o el PIN correctos podrán iniciar sesión en ese el dispositivo. 

Para poder acceder a los recursos educativos o profesionales, es posible que su organización le obligue a cifrar el dispositivo Android. Algunos de los dispositivos Android más recientes se suministran ya cifrados de forma predeterminada.  

## <a name="turn-on-encryption"></a>Activación del cifrado

Haga lo siguiente si el Portal de empresa o la aplicación Microsoft Intune le pide cifrar el dispositivo. 

> [!Note]
> Algunos dispositivos Android de Huawei, Vivo y OPPO no se pueden cifrar. Descubra más [aquí](your-device-appears-encrypted-but-cp-says-otherwise-android.md).  

1. Establezca un bloqueo de pantalla del dispositivo.  
    a. Vaya a **Configuración** > **Pantalla de bloqueo y seguridad** > **Tipo de bloqueo de pantalla**.  
    b. Seleccione **PIN**, **Contraseña** o **Patrón**.  
    c. Siga las instrucciones en pantalla para configurar el bloqueo de pantalla.  

2. Vuelva a **Pantalla de bloqueo de seguridad** y seleccione **Inicio seguro**.
3. Elija **Require PIN when device turns on** (Requerir PIN cuando el dispositivo se active) > **Aceptar**.
4. Escriba el PIN para confirmar y cifrar el dispositivo.
5. Abra la aplicación Portal de empresa o Microsoft Intune.
    * Usuarios se Portal de empresa: seleccione el dispositivo y pulse en **Comprobar configuración del dispositivo**. 
    * Usuarios de Microsoft Intune: tendrán que esperar hasta que se actualice la página, pero cuando lo haga, el estado de cifrado debe haber cambiado a compatible.  

Los dispositivos que ejecuten Android 4.4 y versiones anteriores pueden no tener la opción **Inicio seguro**. En ese caso, complete los pasos siguientes para cifrar el dispositivo.

1. Vaya a **Configuración** > **Seguridad** > **Cifrar dispositivo**. Las etiquetas en pantalla varían de un dispositivo Android a otro. Si no ve la opción **Cifrar dispositivo**, pruebe con:
    * **Almacenamiento** > **Cifrado del almacenamiento**
    * **Almacenamiento** > **Pantalla de bloqueo de seguridad** > **Configuración adicional de seguridad** 

2. Siga las instrucciones en pantalla. Durante el cifrado, es posible que el dispositivo se reinicie varias veces.
3. Abra la aplicación Portal de empresa o Microsoft Intune.
    * Usuarios se Portal de empresa: seleccione el dispositivo y pulse en **Comprobar configuración del dispositivo**.  
    * Usuarios de Microsoft Intune: tendrán que esperar hasta que se actualice la página, pero cuando lo haga, el estado de cifrado debe haber cambiado a compatible.

## <a name="troubleshoot"></a>Solución de problemas  
**Problema**: ya cifró el dispositivo y

- El botón de cifrado está deshabilitado.
- Ve un mensaje en el que se indica que aún es necesario realizar el cifrado.
- Obtiene errores al intentar usar el Portal de empresa o la aplicación Microsoft Intune.

**Opciones que puede probar**

- Asegúrese de que el dispositivo está cargado y conectado.  
- Asegúrese de que ha establecido un PIN o una contraseña en el dispositivo.  

¿Aún necesita ayuda? Póngase en contacto con el equipo de soporte técnico de su empresa (visite el [sitio web del Portal de empresa](https://go.microsoft.com/fwlink/?linkid=2010980) para obtener la información de contacto), o escriba al <a href="mailto:wintunedroidfbk@microsoft.com?subject=I'm having trouble with encryption on my Android device&body=Describe the issue you're experiencing here.">equipo de Microsoft Android</a>.  