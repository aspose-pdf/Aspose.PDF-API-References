---
title: Document.Document
second_title: Aspose.PDF for .NET API Reference
description: Constructor de Documento. Inicializa una nueva instancia de Documento desde el flujo de entrada
type: docs
weight: 10
url: /es/net/aspose.pdf/document/document/
---
## Documento(Stream) {#constructor_2}

Inicializa una nueva instancia de Documento desde el *flujo* de entrada.

```csharp
public Document(Stream input)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | Stream | Flujo con documento pdf. |

### Ver También

* clase [Documento](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Documento(Stream, bool) {#constructor_4}

Inicializa una nueva instancia de Documento desde el *flujo* de entrada.

```csharp
public Document(Stream input, bool isManagedStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | Stream | Flujo con documento pdf. |
| isManagedStream | Boolean | si se establece en `true`, el flujo interno se cierra antes de salir; de lo contrario, no. |

### Ver También

* clase [Documento](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Documento(Stream, string) {#constructor_5}

Inicializa una nueva instancia de Documento desde el *flujo* de entrada.

```csharp
public Document(Stream input, string password)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | Stream | Objeto de flujo de entrada, el pdf correspondiente está protegido por contraseña. |
| password | String | Contraseña de usuario o propietario. |

### Ver También

* clase [Documento](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Documento(Stream, string, bool) {#constructor_6}

Inicializa una nueva instancia de Documento desde el *flujo* de entrada.

```csharp
public Document(Stream input, string password, bool isManagedStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | Stream | Flujo con documento pdf. |
| password | String | Contraseña de usuario o propietario. |
| isManagedStream | Boolean | Si se establece en `true`, el flujo interno se cierra antes de salir; de lo contrario, no. |

### Ver También

* clase [Documento](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Documento(string) {#constructor_7}

Solo inicializa Documento usando *nombre de archivo*. Lo mismo que `Documento`.

```csharp
public Document(string filename)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | String | El nombre del archivo del documento pdf. |

### Ver También

* clase [Documento](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Documento(string, bool) {#constructor_9}

Solo inicializa Documento usando *nombre de archivo*. Lo mismo que `Documento`.

```csharp
public Document(string filename, bool isManagedStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | String | El nombre del archivo del documento pdf. |
| isManagedStream | Boolean | Si se establece en `true`, el flujo interno se cierra antes de salir; de lo contrario, no. |

### Ver También

* clase [Documento](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Documento(string, string) {#constructor_10}

Inicializa una nueva instancia de la clase [`Documento`](../) para trabajar con documentos encriptados.

```csharp
public Document(string filename, string password)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | String | Nombre del archivo del documento. |
| password | String | Contraseña de usuario o propietario. |

### Ver También

* clase [Documento](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Documento(string, string, bool) {#constructor_11}

Inicializa una nueva instancia de la clase [`Documento`](../) para trabajar con documentos encriptados.

```csharp
public Document(string filename, string password, bool isManagedStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | String | Nombre del archivo del documento. |
| password | String | Contraseña de usuario o propietario. |
| isManagedStream | Boolean | si se establece en `true`, el flujo interno se cierra antes de salir; de lo contrario, no. |

### Ver También

* clase [Documento](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Documento() {#constructor}

Inicializa un documento vacío.

```csharp
public Document()
```

### Ver También

* clase [Documento](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Documento(PdfVersion) {#constructor_1}

Inicializa un documento vacío por versión.

```csharp
public Document(PdfVersion version)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| version | PdfVersion | La versión del PDF. |

### Ver También

* enum [PdfVersion](../../pdfversion/)
* clase [Documento](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Documento(string, LoadOptions) {#constructor_8}

Abre un documento existente desde un archivo proporcionando las opciones de conversión necesarias para obtener el documento pdf.

```csharp
public Document(string filename, LoadOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | String | Archivo de entrada para convertir en documento pdf. |
| options | LoadOptions | Representa propiedades para convertir *filename* en documento pdf. |

### Ver También

* clase [LoadOptions](../../loadoptions/)
* clase [Documento](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Documento(Stream, LoadOptions) {#constructor_3}

Abre un documento existente desde un flujo proporcionando la conversión necesaria para obtener el documento pdf.

```csharp
public Document(Stream input, LoadOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | Stream | Flujo de entrada para convertir en documento pdf. |
| options | LoadOptions | Representa propiedades para convertir *input* en documento pdf. |

### Ver También

* clase [LoadOptions](../../loadoptions/)
* clase [Documento](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)