---
title: OptimizedMemoryStream.Read
second_title: Aspose.PDF for .NET API Reference
description: Método OptimizedMemoryStream. Cuando se anula en una clase derivada, lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo por el número de bytes leídos
type: docs
weight: 100
url: /es/net/aspose.pdf/optimizedmemorystream/read/
---
## Método OptimizedMemoryStream.Read

Cuando se anula en una clase derivada, lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo por el número de bytes leídos.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | Byte[] | Un arreglo de bytes. Cuando este método retorna, el buffer contiene el arreglo de bytes especificado con los valores |
| offset | Int32 | El desplazamiento de bytes basado en cero en el que comenzar a almacenar los datos leídos del flujo actual. |
| count | Int32 | El número máximo de bytes que se leerán del flujo actual. |

### Valor de Retorno

El número total de bytes leídos en el buffer. Esto puede ser menor que el número de bytes solicitados si no hay suficientes bytes disponibles actualmente, o cero (0) si se ha alcanzado el final del flujo.

### Véase También

* clase [OptimizedMemoryStream](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)