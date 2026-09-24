---
title: "Document.Save"
linktitle: "Save"
articleTitle: "Save"
second_title: "Aspose.PDF for .NET API Reference"
description: "Document method. Stores document into stream."
type: docs
weight: 250
url: "/net/aspose.pdf/document/save/"
product_version: "26.9.0"
---
## Save(Stream) {#save}

Stores document into stream.

```csharp
public void Save(Stream output)
```

| Parameter | Type | Description |
| --- | --- | --- |
| output | Stream | Stream where document shell be stored. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string) {#save_1}

Saves document into the specified file.

```csharp
public void Save(string outputFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | string | Path to file where the document will be stored. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save() {#save_2}

Save document incrementally (i.e. using incremental update technique).

In order to save document incrementally we should open the document file for writing. 
 Therefore Document must be initialized with writable stream like in the next code snippet:
 Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite));
 // make some changes and save the document incrementally
 doc.Save();

```csharp
public void Save()
```

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save([SaveOptions](../../../aspose.pdf/saveoptions/)) {#save_3}

Saves the document with save options.

```csharp
public void Save(SaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | SaveOptions | Save options. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, [SaveFormat](../../../aspose.pdf.lowcode/saveformat/)) {#save_4}

Saves the document with a new name along with a file format.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | string | Path to file where the document will be stored. |
| format | SaveFormat | Format options. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, [SaveFormat](../../../aspose.pdf.lowcode/saveformat/)) {#save_5}

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
| ArgumentException | <see cref="T:System.ArgumentException" /> when <see cref="T:Aspose.Pdf.HtmlSaveOptions" /> is passed to a method. Save a document to the html stream is not supported. Please use method save to the file. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, [SaveOptions](../../../aspose.pdf/saveoptions/)) {#save_6}

Saves the document with a new name setting its save options.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | string | Path to file where the document will be stored. |
| options | SaveOptions | Save options. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, [SaveOptions](../../../aspose.pdf/saveoptions/)) {#save_7}

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
| ArgumentException | <see cref="T:System.ArgumentException" /> when <see cref="T:Aspose.Pdf.HtmlSaveOptions" /> is passed to a method. Save a document to the html stream is not supported. Please use method save to the file. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

