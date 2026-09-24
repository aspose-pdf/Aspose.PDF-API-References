---
title: "Document.SaveAsync"
linktitle: "SaveAsync"
articleTitle: "SaveAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "Document method. Stores document into stream."
type: docs
weight: 260
url: "/net/aspose.pdf/document/saveasync/"
product_version: "26.9.0"
---
## SaveAsync(Stream, CancellationToken) {#saveasync}

Stores document into stream.

```csharp
public Task SaveAsync(Stream output, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| output | Stream | Stream where document shell be stored. |
| cancellationToken | CancellationToken | Caclellation token. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

Asynchronous task.

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_1}

Saves document into the specified file.

```csharp
public Task SaveAsync(string outputFileName, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | string | Path to file where the document will be stored. |
| cancellationToken | CancellationToken | Caclellation token. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

Asynchronous task.

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(CancellationToken) {#saveasync_2}

Save document incrementally (i.e. using incremental update technique).

In order to save document incrementally we should open the document file for writing. 
 Therefore Document must be initialized with writable stream like in the next code snippet:
 Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite));
 // make some changes and save the document incrementally
 doc.Save();

```csharp
public Task SaveAsync(CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| cancellationToken | CancellationToken | Caclellation token. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

Asynchronous task.

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync([SaveOptions](../../../aspose.pdf/saveoptions/), CancellationToken) {#saveasync_3}

Saves the document with save options.

```csharp
public Task SaveAsync(SaveOptions options, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | SaveOptions | Save options. |
| cancellationToken | CancellationToken | Caclellation token. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

Asynchronous task.

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, [SaveFormat](../../../aspose.pdf.lowcode/saveformat/), CancellationToken) {#saveasync_4}

Saves the document with a new name along with a file format.

```csharp
public Task SaveAsync(string outputFileName, SaveFormat format, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | string | Path to file where the document will be stored. |
| format | SaveFormat | Format options. |
| cancellationToken | CancellationToken | Caclellation token. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

Asynchronous task.

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, [SaveFormat](../../../aspose.pdf.lowcode/saveformat/), CancellationToken) {#saveasync_5}

Saves the document with a new name along with a file format.

```csharp
public Task SaveAsync(Stream outputStream, SaveFormat format, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Stream where the document will be stored. |
| format | SaveFormat | Format options. |
| cancellationToken | CancellationToken | Cancellation token |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

Asynchronous task.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | <see cref="T:System.ArgumentException" /> when <see cref="T:Aspose.Pdf.HtmlSaveOptions" /> is passed to a method. Save a document to the html stream is not supported. Please use method save to the file. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, [SaveOptions](../../../aspose.pdf/saveoptions/), CancellationToken) {#saveasync_6}

Saves the document with a new name setting its save options.

```csharp
public Task SaveAsync(string outputFileName, SaveOptions options, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | string | Path to file where the document will be stored. |
| options | SaveOptions | Save options. |
| cancellationToken | CancellationToken | Caclellation token. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

Asynchronous task.

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, [SaveOptions](../../../aspose.pdf/saveoptions/), CancellationToken) {#saveasync_7}

Saves the document to a stream with a save options.

```csharp
public Task SaveAsync(Stream outputStream, SaveOptions options, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Stream where the document will be stored. |
| options | SaveOptions | Save options. |
| cancellationToken | CancellationToken | Caclellation token. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

Asynchronous task.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | <see cref="T:System.ArgumentException" /> when <see cref="T:Aspose.Pdf.HtmlSaveOptions" /> is passed to a method. Save a document to the html stream is not supported. Please use method save to the file. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

