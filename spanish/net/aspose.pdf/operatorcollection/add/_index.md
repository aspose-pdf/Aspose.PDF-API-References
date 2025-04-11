---
title: OperatorCollection.Add
second_title: Aspose.PDF for .NET API Reference
description: Método OperatorCollection. Agrega un nuevo operador a la colección
type: docs
weight: 60
url: /es/net/aspose.pdf/operatorcollection/add/
---
## Add(Operator) {#add}

Agrega un nuevo operador a la colección.

```csharp
public override void Add(Operator op)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| op | Operator | Operador que debe ser agregado |

## Ejemplos

El ejemplo demuestra cómo agregar operadores al final de page.contents.

```csharp
Document doc = new Document("input.pdf");
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.q());
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.Q());
```

### Ver También

* clase [Operator](../../operator/)
* clase [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Operator[]) {#add_1}

Agrega operadores al final de los operadores de contenido.

```csharp
public void Add(Operator[] ops)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ops | Operator[] | Array de operadores a ser agregados. Cada operador puede tener cualquier índice (por defecto -1) porque llegan al final de los operadores de contenido, es decir, los índices se asignan automáticamente. |

## Ejemplos

El ejemplo demuestra cómo agregar un operador al final de los contenidos de la página.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Add(new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### Ver También

* clase [Operator](../../operator/)
* clase [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(ICollection&lt;Operator&gt;) {#add_2}

Agrega a la colección todos los operadores de otra colección.

```csharp
public void Add(ICollection<Operator> ops)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ops | ICollection`1 | colección que contiene operadores que serán agregados. |

## Ejemplos

El ejemplo demuestra cómo agregar una colección de operadores a los contenidos de la página.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new AOperator.q());
opList.Add(new Operators.Q());
oc.Add(opList);
```

### Ver También

* clase [Operator](../../operator/)
* clase [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)