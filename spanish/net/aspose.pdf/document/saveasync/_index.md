---
title: Document.SaveAsync
second_title: Aspose.PDF for .NET API Reference
description: Método del documento. Almacena el documento en el flujo
type: docs
weight: 840
url: /es/net/aspose.pdf/document/saveasync/
---
## SaveAsync(Stream, CancellationToken) {#saveasync_3}

Almacena el documento en el flujo.

```csharp
public Task SaveAsync(Stream output, CancellationToken cancellationToken)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| output | Stream | Flujo donde se almacenará el documento. |
| cancellationToken | CancellationToken | Token de cancelación. |

### Valor de retorno

Tarea asíncrona.

### Véase también

* clase [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_6}

Guarda el documento en el archivo especificado.

```csharp
public Task SaveAsync(string outputFileName, CancellationToken cancellationToken)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFileName | String | Ruta al archivo donde se almacenará el documento. |
| cancellationToken | CancellationToken | Token de cancelación. |

### Valor de retorno

Tarea asíncrona.

### Véase también

* clase [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(CancellationToken) {#saveasync_7}

Guarda el documento de forma incremental (es decir, utilizando la técnica de actualización incremental).

```csharp
public Task SaveAsync(CancellationToken cancellationToken)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cancellationToken | CancellationToken | Token de cancelación. |

### Valor de retorno

Tarea asíncrona.

## Observaciones

Para guardar el documento de forma incremental, debemos abrir el archivo del documento para escritura. Por lo tanto, el Documento debe ser inicializado con un flujo escribible como en el siguiente fragmento de código: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // hacer algunos cambios y guardar el documento de forma incremental doc.Save();

### Véase también

* clase [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(SaveOptions, CancellationToken) {#saveasync}

Guarda el documento con opciones de guardado.

```csharp
public Task SaveAsync(SaveOptions options, CancellationToken cancellationToken)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | SaveOptions | Opciones de guardado. |
| cancellationToken | CancellationToken | Token de cancelación. |

### Valor de retorno

Tarea asíncrona.

### Véase también

* clase [SaveOptions](../../saveoptions/)
* clase [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveFormat, CancellationToken) {#saveasync_4}

Guarda el documento con un nuevo nombre junto con un formato de archivo.

```csharp
public Task SaveAsync(string outputFileName, SaveFormat format, CancellationToken cancellationToken)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFileName | String | Ruta al archivo donde se almacenará el documento. |
| format | SaveFormat | Opciones de formato. |
| cancellationToken | CancellationToken | Token de cancelación. |

### Valor de retorno

Tarea asíncrona.

### Véase también

* enum [SaveFormat](../../saveformat/)
* clase [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveFormat, CancellationToken) {#saveasync_1}

Guarda el documento con un nuevo nombre junto con un formato de archivo.

```csharp
public Task SaveAsync(Stream outputStream, SaveFormat format, CancellationToken cancellationToken)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | Stream | Flujo donde se almacenará el documento. |
| format | SaveFormat | Opciones de formato. |
| cancellationToken | CancellationToken | Token de cancelación. |

### Valor de retorno

Tarea asíncrona.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | ArgumentException cuando se pasa [`HtmlSaveOptions`](../../htmlsaveoptions/) a un método. Guardar un documento en el flujo html no es compatible. Por favor, use el método guardar en el archivo. |

### Véase también

* enum [SaveFormat](../../saveformat/)
* clase [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveOptions, CancellationToken) {#saveasync_5}

Guarda el documento con un nuevo nombre configurando sus opciones de guardado.

```csharp
public Task SaveAsync(string outputFileName, SaveOptions options, 
    CancellationToken cancellationToken)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFileName | String | Ruta al archivo donde se almacenará el documento. |
| options | SaveOptions | Opciones de guardado. |
| cancellationToken | CancellationToken | Token de cancelación. |

### Valor de retorno

Tarea asíncrona.

### Véase también

* clase [SaveOptions](../../saveoptions/)
* clase [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveOptions, CancellationToken) {#saveasync_2}

Guarda el documento en un flujo con opciones de guardado.

```csharp
public Task SaveAsync(Stream outputStream, SaveOptions options, CancellationToken cancellationToken)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | Stream | Flujo donde se almacenará el documento. |
| options | SaveOptions | Opciones de guardado. |
| cancellationToken | CancellationToken | Token de cancelación. |

### Valor de retorno

Tarea asíncrona.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | ArgumentException cuando se pasa [`HtmlSaveOptions`](../../htmlsaveoptions/) a un método. Guardar un documento en el flujo html no es compatible. Por favor, use el método guardar en el archivo. |

### Véase también

* clase [SaveOptions](../../saveoptions/)
* clase [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)