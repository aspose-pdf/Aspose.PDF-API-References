---
title: "System::Reflection::FieldAttributes enum"
linktitle: "FieldAttributes"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Reflection::FieldAttributes enum. Atributos de campo reflejados en C++."
type: docs
weight: 1200
url: /es/cpp/system.reflection/fieldattributes/
---
## FieldAttributes enum


Atributos de campo reflejados.

```cpp
enum class FieldAttributes
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| FieldAccessMask | 7 | Máscara de acceso a miembros. Use esta máscara para obtener información de accesibilidad. |
| PrivateScope | 0 | Miembros no referenciables. |
| Privado | 1 | Miembros privados. |
| FamANDAssem | 2 | Miembros privados y con alcance de ensamblado. |
| Assembly | 3 | Miembros con alcance de ensamblado. |
| Family | 4 | Miembros accesibles por tipo y subtipos. |
| FamORAssem | 5 | Miembros accesibles por tipo, subtipos y ensamblado. |
| Public | 6 | Miembros accesibles por cualquiera. |
| Estático | 16 | Miembros estáticos como opuesto a los miembros de instancia. |
| InitOnly | 32 | Miembros const que solo pueden ser inicializados pero no modificados. |
| Literal | 64 | Miembros constantes en tiempo de compilación. |
| NotSerialized | 128 | Miembros no serializados. |
| SpecialName | 512 | Campo especial de uno de los nombres siguientes. |
| PinvokeImpl | 8192 | Implementación reenviada de Interop. |
| ReservedMask | 38144 | Banderas reservadas solo para uso en tiempo de ejecución. |
| RTSpecialName | 1024 | El tiempo de ejecución debería comprobar la codificación del nombre. |
| HasFieldMarshal | 4096 | La información de marshaling está presente. |
| HasDefault | 32768 | El valor predeterminado está presente. |
| HasFieldRVA | 256 | RVA está presente. |

## Ver también

* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
