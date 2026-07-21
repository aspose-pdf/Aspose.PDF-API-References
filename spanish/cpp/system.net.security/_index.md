---
title: "Espacio de nombres System::Net::Security"
linktitle: "System::Net::Security"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Cómo usar el espacio de nombres System::Net::Security en C++."
type: docs
weight: 5400
url: /es/cpp/system.net.security/
---



## Clases

| Clase | Descripción |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | Contiene los métodos para pasar credenciales a través de un flujo. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [SslStream](./sslstream/) | Un flujo que utiliza el protocolo SSL para autenticar al servidor y, opcionalmente, al cliente. |
## Enums

| Enumeración | Descripción |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | Indicadores de autenticación específicos de WebRequest. |
| [EncryptionPolicy](./encryptionpolicy/) | Enumera las políticas de cifrado. |
| [SslPolicyErrors](./sslpolicyerrors/) | Enumera los errores de política de SSL. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | Un delegado de usuario utilizado para seleccionar el certificado SSL local. |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | Un delegado de usuario utilizado para verificar el certificado SSL remoto. |
