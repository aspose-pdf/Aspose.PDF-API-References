---
title: Document.Save
second_title: Aspose.PDF for .NET API Reference
description: Método Document. Almacena el documento en un flujo
type: docs
weight: 830
url: /es/net/aspose.pdf/document/save/
---
## Save(Stream) {#save_2}

Almacena el documento en un flujo.

```csharp
public void Save(Stream output)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| output | Stream | Flujo donde se almacenará el documento. |

### Ver También

* clase [Document](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

Guarda el documento en el archivo especificado.

```csharp
public void Save(string outputFileName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFileName | String | Ruta al archivo donde se almacenará el documento. |

### Ver También

* clase [Document](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Save() {#save}

Guarda el documento de manera incremental (es decir, utilizando la técnica de actualización incremental).

```csharp
public void Save()
```

## Observaciones

Para guardar el documento de manera incremental, debemos abrir el archivo del documento para escritura. Por lo tanto, Document debe ser inicializado con un flujo escribible como en el siguiente fragmento de código: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // realiza algunos cambios y guarda el documento de manera incremental doc.Save();

### Ver También

* clase [Document](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

Guarda el documento con opciones de guardado.

```csharp
public void Save(SaveOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | SaveOptions | Opciones de guardado. |

### Ver También

* clase [SaveOptions](../../saveoptions/)
* clase [Document](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

Guarda el documento con un nuevo nombre junto con un formato de archivo.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFileName | String | Ruta al archivo donde se almacenará el documento. |
| format | SaveFormat | Opciones de formato. |

### Ver También

* enum [SaveFormat](../../saveformat/)
* clase [Document](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

Guarda el documento con un nuevo nombre junto con un formato de archivo.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | Stream | Flujo donde se almacenará el documento. |
| format | SaveFormat | Opciones de formato. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | ArgumentException cuando [`HtmlSaveOptions`](../../htmlsaveoptions/) se pasa a un método. Guardar un documento en el flujo html no es compatible. Por favor, use el método guardar en el archivo. |

### Ver También

* enum [SaveFormat](../../saveformat/)
* clase [Document](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Save(string, SaveOptions) {#save_7}

Guarda el documento con un nuevo nombre configurando sus opciones de guardado.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFileName | String | Ruta al archivo donde se almacenará el documento. |
| options | SaveOptions | Opciones de guardado. |

### Ver También

* clase [SaveOptions](../../saveoptions/)
* clase [Document](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Save(Stream, SaveOptions) {#save_4}

Guarda el documento en un flujo con opciones de guardado.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | Stream | Flujo donde se almacenará el documento. |
| options | SaveOptions | Opciones de guardado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | ArgumentException cuando [`HtmlSaveOptions`](../../htmlsaveoptions/) se pasa a un método. Guardar un documento en el flujo html no es compatible. Por favor, use el método guardar en el archivo. |

### Ver También

* clase [SaveOptions](../../saveoptions/)
* clase [Document](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)