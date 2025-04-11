---
title: ComHelper.OpenStream
second_title: Aspose.PDF for .NET API Reference
description: Método ComHelper. Inicializa y devuelve una nueva instancia de Document desde el flujo de entrada
type: docs
weight: 30
url: /es/net/aspose.pdf/comhelper/openstream/
---
## OpenStream(Stream) {#openstream}

Inicializa y devuelve una nueva instancia de Document desde el *flujo* de entrada.

```csharp
public Document OpenStream(Stream input)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | Stream | Flujo con documento pdf. |

### Valor de Retorno

Objeto Document

### Véase También

* clase [Document](../../document/)
* clase [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, string) {#openstream_3}

Inicializa y devuelve una nueva instancia de Document desde el *flujo* de entrada.

```csharp
public Document OpenStream(Stream input, string password)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | Stream | Objeto de flujo de entrada, el pdf correspondiente está protegido por contraseña. |
| password | String | Contraseña de usuario o propietario. |

### Valor de Retorno

Objeto Document

### Véase También

* clase [Document](../../document/)
* clase [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, bool) {#openstream_2}

Inicializa y devuelve una nueva instancia de Document desde el *flujo* de entrada.

```csharp
public Document OpenStream(Stream input, bool isManagedStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | Stream | Flujo con documento pdf. |
| isManagedStream | Boolean | si se establece en `true`, el flujo interno se cierra antes de salir; de lo contrario, no. |

### Valor de Retorno

Objeto Document

### Véase También

* clase [Document](../../document/)
* clase [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, string, bool) {#openstream_4}

Inicializa y devuelve una nueva instancia de Document desde el *flujo* de entrada.

```csharp
public Document OpenStream(Stream input, string password, bool isManagedStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | Stream | Flujo con documento pdf. |
| password | String | Contraseña de usuario o propietario. |
| isManagedStream | Boolean | si se establece en `true`, el flujo interno se cierra antes de salir; de lo contrario, no. |

### Valor de Retorno

Objeto Document

### Véase También

* clase [Document](../../document/)
* clase [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, LoadOptions) {#openstream_1}

Abre y devuelve un documento existente desde un flujo proporcionando la conversión necesaria para obtener el documento pdf.

```csharp
public Document OpenStream(Stream input, LoadOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | Stream | Flujo de entrada para convertir en documento pdf. |
| options | LoadOptions | Representa propiedades para convertir *input* en documento pdf. |

### Valor de Retorno

Objeto Document

### Véase También

* clase [Document](../../document/)
* clase [LoadOptions](../../loadoptions/)
* clase [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)