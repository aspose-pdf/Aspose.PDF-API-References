---
title: Process
second_title: Referencia de API de Aspose.PDF para .NET
description: Cada dispositivo representa alguna operación en el documento por ejemplo podemos convertir un documento pdf a otro formato.
type: docs
weight: 20
url: /es/net/aspose.pdf.devices/documentdevice/process/
---
## Process(Document, int, int, Stream) {#process}

Cada dispositivo representa alguna operación en el documento, por ejemplo, podemos convertir un documento pdf a otro formato.

```csharp
public abstract void Process(Document document, int fromPage, int toPage, Stream output)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Document | El documento a procesar. |
| fromPage | Int32 | Define la página desde la que empezar a procesar. |
| toPage | Int32 | Define la última página a procesar. |
| output | Stream | Define el flujo donde se almacenan los resultados del procesamiento. |

### Ver también

* class [Document](../../../aspose.pdf/document)
* class [DocumentDevice](../../documentdevice)
* espacio de nombres [Aspose.Pdf.Devices](../../documentdevice)
* asamblea [Aspose.PDF](../../../)

---

## Process(Document, Stream) {#process_2}

Procesa todo el documento y guarda los resultados en el flujo.

```csharp
public void Process(Document document, Stream output)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Document | El documento a procesar. |
| output | Stream | Define el flujo donde se almacenan los resultados del procesamiento. |

### Ver también

* class [Document](../../../aspose.pdf/document)
* class [DocumentDevice](../../documentdevice)
* espacio de nombres [Aspose.Pdf.Devices](../../documentdevice)
* asamblea [Aspose.PDF](../../../)

---

## Process(Document, string) {#process_3}

Procesa todo el documento y guarda los resultados en un archivo.

```csharp
public void Process(Document document, string outputFileName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Document | El documento a procesar. |
| outputFileName | String | Define el archivo donde se almacenan los resultados del procesamiento. |

### Ver también

* class [Document](../../../aspose.pdf/document)
* class [DocumentDevice](../../documentdevice)
* espacio de nombres [Aspose.Pdf.Devices](../../documentdevice)
* asamblea [Aspose.PDF](../../../)

---

## Process(Document, int, int, string) {#process_1}

Procesa ciertas páginas del documento y guarda los resultados en un archivo.

```csharp
public void Process(Document document, int fromPage, int toPage, string outputFileName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Document | El documento a procesar. |
| fromPage | Int32 | La primera página para comenzar a procesar. |
| toPage | Int32 | La última página de procesamiento. |
| outputFileName | String | Define el archivo donde se almacenan los resultados del procesamiento. |

### Ver también

* class [Document](../../../aspose.pdf/document)
* class [DocumentDevice](../../documentdevice)
* espacio de nombres [Aspose.Pdf.Devices](../../documentdevice)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->