---
title: Form.Add
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Agrega un campo en el formulario
type: docs
weight: 190
url: /es/net/aspose.pdf.forms/form/add/
---
## Add(Field, int) {#add_2}

Agrega un campo en el formulario.

```csharp
public void Add(Field field, int pageNumber)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| field | Field | Campo que debe ser agregado. |
| pageNumber | Int32 | Índice de la página donde se colocará el campo agregado. |

### Ver También

* clase [Field](../../field/)
* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* ensamblado [Aspose.PDF](../../../)

---

## Add(Field) {#add_1}

Agrega un campo en el formulario.

```csharp
public void Add(Field field)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| field | Field | Campo que debe ser agregado. |

### Ver También

* clase [Field](../../field/)
* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* ensamblado [Aspose.PDF](../../../)

---

## Add(Field, string, int) {#add}

Agrega un nuevo campo al formulario; Si este campo ya está colocado en otro formulario o en este, se crea una copia del campo.

```csharp
public Field Add(Field field, string partialName, int pageNumber)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| field | Field | Nombre del campo. |
| partialName | String | Nombre del campo en el formulario. |
| pageNumber | Int32 | Número de página donde se agregará el campo. |

### Valor de Retorno

Campo agregado devuelto. Si se creó una copia del campo, será devuelta.

### Ver También

* clase [Field](../../field/)
* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* ensamblado [Aspose.PDF](../../../)