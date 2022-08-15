---
title: Save
second_title: Referencia de API de Aspose.PDF para .NET
description: Guarde el documento de forma incremental es decir utilizando la técnica de actualización incremental.
type: docs
weight: 720
url: /es/net/aspose.pdf/document/save/
---
## Save() {#save}

Guarde el documento de forma incremental (es decir, utilizando la técnica de actualización incremental).

```csharp
public void Save()
```

### Observaciones

Para guardar el documento de forma incremental, debemos abrir el archivo del documento para escribir. Por lo tanto, el documento debe inicializarse con un flujo de escritura como en el siguiente fragmento de código: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // realice algunos cambios y guarde el documento incrementaly doc.Save();

### Ver también

* class [Document](../../document)
* espacio de nombres [Aspose.Pdf](../../document)
* asamblea [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

Guarda el documento con opciones de guardado.

```csharp
public void Save(SaveOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| options | SaveOptions | Guardar opciones. |

### Ver también

* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* espacio de nombres [Aspose.Pdf](../../document)
* asamblea [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

Guarda el documento con un nuevo nombre junto con un formato de archivo.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFileName | String | Ruta al archivo donde se almacenará el documento. |
| format | SaveFormat | Opciones de formato. |

### Ver también

* enum [SaveFormat](../../saveformat)
* class [Document](../../document)
* espacio de nombres [Aspose.Pdf](../../document)
* asamblea [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

Guarda el documento con un nuevo nombre junto con un formato de archivo.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | Stream donde se almacenará el documento. |
| format | SaveFormat | Opciones de formato. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | ArgumentException cuando[`HtmlSaveOptions`](../../htmlsaveoptions) se pasa a un método. No se admite guardar un documento en la secuencia html. Utilice el método guardar en el archivo. |

### Ver también

* enum [SaveFormat](../../saveformat)
* class [Document](../../document)
* espacio de nombres [Aspose.Pdf](../../document)
* asamblea [Aspose.PDF](../../../)

---

## Save(string, SaveOptions) {#save_7}

Guarda el documento con un nuevo nombre configurando sus opciones de guardado.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFileName | String | Ruta al archivo donde se almacenará el documento. |
| options | SaveOptions | Guardar opciones. |

### Ver también

* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* espacio de nombres [Aspose.Pdf](../../document)
* asamblea [Aspose.PDF](../../../)

---

## Save(Stream, SaveOptions) {#save_4}

Guarda el documento en una secuencia con opciones de guardado.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | Stream donde se almacenará el documento. |
| options | SaveOptions | Guardar opciones. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | ArgumentException cuando[`HtmlSaveOptions`](../../htmlsaveoptions) se pasa a un método. No se admite guardar un documento en la secuencia html. Utilice el método guardar en el archivo. |

### Ver también

* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* espacio de nombres [Aspose.Pdf](../../document)
* asamblea [Aspose.PDF](../../../)

---

## Save(HttpResponse, string, ContentDisposition, SaveOptions) {#save_8}

Guarda el documento en un flujo de respuesta con opciones de guardado.

```csharp
public void Save(HttpResponse response, string outputFileName, ContentDisposition disposition, 
    SaveOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| response | HttpResponse | Encapsula la información de respuesta HTTP. |
| outputFileName | String | Nombre de archivo simple, es decir, sin ruta. |
| disposition | ContentDisposition | Representa un encabezado de disposición de contenido del protocolo MIME. |
| options | SaveOptions | Guardar opciones. |

### Ver también

* enum [ContentDisposition](../../contentdisposition)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* espacio de nombres [Aspose.Pdf](../../document)
* asamblea [Aspose.PDF](../../../)

---

## Save(Stream) {#save_2}

Almacena el documento en stream.

```csharp
public void Save(Stream output)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| output | Stream | Secuencia donde se almacenará la carcasa del documento. |

### Ver también

* class [Document](../../document)
* espacio de nombres [Aspose.Pdf](../../document)
* asamblea [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

Guarda el documento en el archivo especificado.

```csharp
public void Save(string outputFileName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFileName | String | Ruta al archivo donde se almacenará el documento. |

### Ver también

* class [Document](../../document)
* espacio de nombres [Aspose.Pdf](../../document)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
