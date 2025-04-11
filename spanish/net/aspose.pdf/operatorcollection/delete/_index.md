---
title: OperatorCollection.Delete
second_title: Aspose.PDF for .NET API Reference
description: Método OperatorCollection. Elimina el operador de la colección
type: docs
weight: 110
url: /es/net/aspose.pdf/operatorcollection/delete/
---
## Delete(int) {#delete_1}

Elimina el operador de la colección.

```csharp
public void Delete(int index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Índice del operador que debe ser eliminado. La numeración de los operadores comienza desde 1. |

## Ejemplos

El ejemplo demuestra cómo eliminar un operador por su índice.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(3);
```

### Ver También

* clase [OperatorCollection](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Delete(Operator[]) {#delete}

Elimina operadores de la colección.

```csharp
public void Delete(Operator[] ops)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ops | Operator[] | Array de operadores a eliminar |

## Ejemplos

El ejemplo demuestra cómo eliminar un operador del contenido de la página.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(new Operator[] { oc[1] } );
```

### Ver También

* clase [Operator](../../operator/)
* clase [OperatorCollection](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Delete(IList&lt;Operator&gt;) {#delete_2}

Elimina operadores de la colección.

```csharp
public void Delete(IList<Operator> list)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| list | IList`1 | La lista de operadores a eliminar |

## Ejemplos

El ejemplo demuestra cómo eliminar un operador del contenido de la página.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(oc[1]);
oc.Delete(opList);
```

### Ver También

* clase [Operator](../../operator/)
* clase [OperatorCollection](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)