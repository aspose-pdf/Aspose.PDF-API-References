---
title: OperatorCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: Método OperatorCollection. Inserta operador en la colección
type: docs
weight: 140
url: /es/net/aspose.pdf/operatorcollection/insert/
---
## Insert(int, Operator) {#insert}

Inserta operador en la colección.

```csharp
public override void Insert(int index, Operator op)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Índice donde se debe agregar el nuevo operador |
| op | Operator | Operador que será insertado |

## Ejemplos

El ejemplo demuestra cómo insertar un operador en el contenido de la página.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Aspose.Pdf.Operators.q());
oc.Add(new Aspose.Pdf.Operators.Q());
```

### Ver También

* clase [Operator](../../operator/)
* clase [OperatorCollection](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Insert(int, Operator[]) {#insert_1}

Inserta operadores en la posición dada.

```csharp
public void Insert(int at, Operator[] ops)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| at | Int32 | Índice desde el cual se comienzan a insertar los operadores. |
| ops | Operator[] | Array de operadores a ser insertados. Cada operador puede tener cualquier índice (por defecto -1) porque sus índices se ajustan automáticamente comenzando desde *at*. |

## Ejemplos

El ejemplo demuestra cómo insertar un operador en el contenido de la página.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### Ver También

* clase [Operator](../../operator/)
* clase [OperatorCollection](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Insert(int, IList&lt;Operator&gt;) {#insert_2}

Inserta operadores en la posición dada.

```csharp
public void Insert(int at, IList<Operator> ops)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| at | Int32 | Índice desde el cual se comienzan a insertar los operadores. |
| ops | IList`1 | Array de operadores a ser insertados. |

## Ejemplos

El ejemplo demuestra cómo insertar operadores en el contenido de la página.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new Operators.q());
opList.Add(new Operators.Q());
oc.Insert(1, opList);
```

### Ver También

* clase [Operator](../../operator/)
* clase [OperatorCollection](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)