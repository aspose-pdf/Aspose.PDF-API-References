---
title: Document.Save
second_title: Aspose.PDF for .NET API Reference
description: Document method. Save document incrementally i.e. using incremental update technique
type: docs
weight: 810
url: /net/aspose.pdf/document/save/
---
## Save() {#save}

Save document incrementally (i.e. using incremental update technique).

```csharp
public void Save()
```

## Remarks

In order to save document incrementally we should open the document file for writing. Therefore Document must be initialized with writable stream like in the next code snippet: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // make some changes and save the document incrementally doc.Save();

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

Saves the document with save options.

```csharp
public void Save(SaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | SaveOptions | Save options. |

### See Also

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

Saves the document with a new name along with a file format.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | String | Path to file where the document will be stored. |
| format | SaveFormat | Format options. |

### See Also

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

Saves the document with a new name along with a file format.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Stream where the document will be stored. |
| format | SaveFormat | Format options. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | ArgumentException when [`HtmlSaveOptions`](../../htmlsaveoptions/) is passed to a method. Save a document to the html stream is not supported. Please use method save to the file. |

### See Also

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveOptions) {#save_7}

Saves the document with a new name setting its save options.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | String | Path to file where the document will be stored. |
| options | SaveOptions | Save options. |

### See Also

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveOptions) {#save_4}

Saves the document to a stream with a save options.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Stream where the document will be stored. |
| options | SaveOptions | Save options. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | ArgumentException when [`HtmlSaveOptions`](../../htmlsaveoptions/) is passed to a method. Save a document to the html stream is not supported. Please use method save to the file. |

### See Also

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(HttpResponse, string, ContentDisposition, SaveOptions) {#save_8}

Saves the document to a response stream with a save options.

```csharp
public void Save(HttpResponse response, string outputFileName, ContentDisposition disposition, 
    SaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| response | HttpResponse | Encapsulates HTTP-response information. |
| outputFileName | String | Simple file name, i.e. without path. |
| disposition | ContentDisposition | Represents a MIME protocol Content-Disposition header. |
| options | SaveOptions | Save options. |

### See Also

* enum [ContentDisposition](../../contentdisposition/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream) {#save_2}

Stores document into stream.

```csharp
public void Save(Stream output)
```

| Parameter | Type | Description |
| --- | --- | --- |
| output | Stream | Stream where document shell be stored. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

Saves document into the specified file.

```csharp
public void Save(string outputFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | String | Path to file where the document will be stored. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


