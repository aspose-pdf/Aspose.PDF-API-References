---
title: Form.HasField
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Verifica si el formulario ya tiene el campo especificado
type: docs
weight: 280
url: /es/net/aspose.pdf.forms/form/hasfield/
---
## HasField(Field) {#hasfield}

Verifica si el formulario ya tiene el campo especificado.

```csharp
public bool HasField(Field field)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| field | Field | Campo a verificar. |

### Valor de Retorno

`true` si el nombre del campo especificado se agregó al Form; de lo contrario, `false`.

### Véase También

* clase [Field](../../field/)
* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* ensamblado [Aspose.PDF](../../../)

---

## HasField(string) {#hasfield_1}

Determina si el campo con el nombre especificado ya se agregó al Form.

```csharp
public bool HasField(string fieldName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) o [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) del campo. |

### Valor de Retorno

`true` si el nombre del campo especificado se agregó al Form; de lo contrario, `false`.

### Véase También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* ensamblado [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

Determina si el campo con el nombre especificado ya se agregó al Form, con la capacidad de buscar en la jerarquía de campos hijos.

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) o [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) del campo. |
| searchChildren | Boolean | Cuando se establece en `true`, se buscará toda la jerarquía de campos del formulario para el *fieldName* solicitado (tenga en cuenta que en este caso se debe pasar el [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) del campo requerido como *fieldName*). |

### Valor de Retorno

`true` si el nombre del campo especificado se agregó al Form; de lo contrario, `false`.

### Véase También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* ensamblado [Aspose.PDF](../../../)