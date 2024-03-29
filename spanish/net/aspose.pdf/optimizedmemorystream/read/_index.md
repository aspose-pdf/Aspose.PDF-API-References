---
title: Read
second_title: Referencia de API de Aspose.PDF para .NET
description: Cuando se anula en una clase derivada lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo según el número de bytes leídos.
type: docs
weight: 100
url: /es/net/aspose.pdf/optimizedmemorystream/read/
---
## OptimizedMemoryStream.Read method

Cuando se anula en una clase derivada, lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo según el número de bytes leídos.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| buffer | Byte[] | Una matriz de bytes. Cuando este método regresa, el búfer contiene la matriz de bytes especificada con los valores |
| offset | Int32 | El desplazamiento de bytes de base cero en el que se comienzan a almacenar los datos leídos del flujo actual. |
| count | Int32 | El número máximo de bytes que se leerán del flujo actual. |

### Valor_devuelto

El número total de bytes leídos en el búfer. Puede ser menor que la cantidad de bytes solicitados si esa cantidad de bytes no está disponible actualmente, o cero (0) si se alcanzó el final de la secuencia.

### Ver también

* class [OptimizedMemoryStream](../../optimizedmemorystream)
* espacio de nombres [Aspose.Pdf](../../optimizedmemorystream)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
