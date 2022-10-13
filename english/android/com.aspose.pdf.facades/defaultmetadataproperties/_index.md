---
title: DefaultMetadataProperties
second_title: Aspose.PDF for Java API Reference
description: Enumeration of standard XMP properties.
type: docs
weight: 17
url: /java/com.aspose.pdf.facades/defaultmetadataproperties/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DefaultMetadataProperties extends System.Enum
```

Enumeration of standard XMP properties.
## Fields

| Field | Description |
| --- | --- |
| [Advisory](#Advisory) | xmp:Advisory property. |
| [BaseURL](#BaseURL) | xmp:BaseURL property. |
| [CreateDate](#CreateDate) | xmp:CreateDate property. |
| [CreatorTool](#CreatorTool) | xmp:CreatorTool property. |
| [Identifier](#Identifier) | xmp:Identifier property. |
| [MetadataDate](#MetadataDate) | xmp:MetadataDate property. |
| [ModifyDate](#ModifyDate) | xmp:ModifyDate property. |
| [Nickname](#Nickname) | xmp:Nickname property. |
| [Thumbnails](#Thumbnails) | xmp:Thumbnails property. |
### Advisory {#Advisory}
```
public static final int Advisory
```


xmp:Advisory property. An unordered array specifying properties that were edited outside the authoring application. Each item should contain a single /// namespace and XPath separated by one ASCII space

### BaseURL {#BaseURL}
```
public static final int BaseURL
```


xmp:BaseURL property. The base URL for relative URLs in the document content. If this document contains Internet links, and those links are relative, /// they are relative to this base URL. This property provides a standard way for embedded relative URLs to be interpreted by tools. /// Web authoring tools should set the value based on their notion of where URLs will be interpreted

### CreateDate {#CreateDate}
```
public static final int CreateDate
```


xmp:CreateDate property. The date and time the resource was originally created.

### CreatorTool {#CreatorTool}
```
public static final int CreatorTool
```


xmp:CreatorTool property. The name of the first known tool used to create the resource.

### Identifier {#Identifier}
```
public static final int Identifier
```


xmp:Identifier property. An unordered array of text strings that unambiguously identify the resource within a given context

### MetadataDate {#MetadataDate}
```
public static final int MetadataDate
```


xmp:MetadataDate property. The date and time that any metadata for this resource was last changed

### ModifyDate {#ModifyDate}
```
public static final int ModifyDate
```


xmp:ModifyDate property. The date and time the resource was last modified.

### Nickname {#Nickname}
```
public static final int Nickname
```


xmp:Nickname property. A short informal name for the resource.

### Thumbnails {#Thumbnails}
```
public static final int Thumbnails
```


xmp:Thumbnails property. An alternative array of thumbnail images for a file, which can differ in characteristics such as size or image encoding.

