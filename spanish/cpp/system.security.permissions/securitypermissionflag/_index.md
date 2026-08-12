---
title: "System::Security::Permissions::SecurityPermissionFlag enumeración"
linktitle: "SecurityPermissionFlag"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Permissions::SecurityPermissionFlag enumeración. Indicadores del permiso de seguridad en C++."
type: docs
weight: 300
url: /es/cpp/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag enum


Banderas del permiso de seguridad.

```cpp
enum class SecurityPermissionFlag
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| NoFlags | 0 | Sin acceso. |
| Aserción | 1 | Asegura que se conceda el permiso. |
| UnmanagedCode | 2 | Llamar código no administrado. |
| OmitirVerificación | 4 | Omitir la verificación del código. |
| Ejecución | 8 | Ejecutar código. |
| ControlarHilo | 16 | Realizar operaciones en hilos. |
| ControlarEvidencia | 32 | Controlar o modificar la evidencia CLR. |
| ControlarPolítica | 64 | Ver y cambiar la política. |
| FormateadorDeSerialización | 128 | Serializar. |
| ControlarPolíticaDeDominio | 256 | Establecer la política de dominio. |
| ControlarPrincipal | 512 | Controlar el objeto principal. |
| ControlarDominioAplicación | 1024 | Controlar el dominio de la aplicación. |
| ConfiguraciónRemota | 2048 | Configurar la comunicación remota. |
| Infraestructura | 4096 | Conectar a la infraestructura CLR. |
| RedireccionesDeEnlace | 8192 | Realizar redirección explícita de enlaces. |
| AllFlags | 16383 | Sin restricciones. |

## Ver también

* Namespace [System::Security::Permissions](../)
* Library [Aspose.PDF for C++](../../)
