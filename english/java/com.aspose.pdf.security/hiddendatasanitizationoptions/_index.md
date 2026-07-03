---
title: HiddenDataSanitizationOptions
second_title: Aspose.PDF for Java API Reference
description: Represents the configuration options for sanitizing hidden data within a document.
type: docs
weight: 10
url: /java/com.aspose.pdf.security/hiddendatasanitizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.HiddenDataSanitizationOptions

```
public final class HiddenDataSanitizationOptions extends Object
```

Represents the configuration options for sanitizing hidden data within a document.

## Constructors

| Constructor | Description |
| --- | --- |
| [HiddenDataSanitizationOptions](#HiddenDataSanitizationOptions--) |  |

## Methods

| Method | Description |
| --- | --- |
| [all](#all--) | Creates a new instance of the {@link HiddenDataSanitizationOptions} class with all options set for sanitization. This includes enabling the removal of annotations, JavaScript, metadata, attachments, search index, private information, flattening of forms and layers, while disabling the option to convert pages to images. Optional configurations like {@code ImageCompressionOptions}({@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}) or {@code ConvertPagesToImages}({@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}) can be manually modified after obtaining the instance, as they are not active by default. |
| [getConvertPagesToImages](#getConvertPagesToImages--) | Gets the option to convert pages to images. If this option is enabled, the ImageCompressionOptions option will be ignored. The option must be enabled manually when using the {@code #All()} method if it is required. The conversion of pages to images will occur after clearing the main hidden data, which is controlled by other options. |
| [getFlattenForms](#getFlattenForms--) | Gets a value indicating whether forms in the document should be flattened during the sanitization process. Flattening forms converts interactive form fields into static content, making them non-editable or fillable. |
| [getFlattenLayers](#getFlattenLayers--) | Gets the option to flatten the layers in the PDF document. When enabled, all layers in the document are merged into a single layer, removing their separate structure. This option is useful for sanitizing documents by simplifying their content and ensuring no hidden data resides within layers. |
| [getImageCompressionOptions](#getImageCompressionOptions--) | Gets the document image conversion option. The option must be enabled manually when using the {@code #All()} method if it is required. |
| [getImageDpi](#getImageDpi--) | Gets the option to resolve page images during conversion. |
| [getRemoveAnnotations](#getRemoveAnnotations--) | Gets a value indicating whether to remove annotations from the document. When enabled, all annotations present in the document will be removed during the sanitization process. Redact annotations will be applied. |
| [getRemoveAttachments](#getRemoveAttachments--) | Gets the option to remove all attached files from the document. When enabled, it ensures that any attachments within the PDF are eliminated during the sanitation process. |
| [getRemoveJavaScriptsAndActions](#getRemoveJavaScriptsAndActions--) | Gets a value indicating whether JavaScript and associated actions should be removed from the document. This option is useful to eliminate potential security vulnerabilities introduced by embedded scripts. |
| [getRemoveMetadata](#getRemoveMetadata--) | Gets an option to remove metadata from the document. If set to true, metadata such as document properties and additional embedded metadata information will be removed during sanitization. |
| [getRemoveSearchIndexAndPrivateInfo](#getRemoveSearchIndexAndPrivateInfo--) | Gets a value indicating whether the search index and private information should be removed from the document. Enables the removal of embedded search indices and private data to enhance document security and privacy. |
| [setConvertPagesToImages](#setConvertPagesToImages-boolean-) | Sets the option to convert pages to images. If this option is enabled, the ImageCompressionOptions option will be ignored. The option must be enabled manually when using the {@code #All()} method if it is required. The conversion of pages to images will occur after clearing the main hidden data, which is controlled by other options. |
| [setFlattenForms](#setFlattenForms-boolean-) | Sets a value indicating whether forms in the document should be flattened during the sanitization process. Flattening forms converts interactive form fields into static content, making them non-editable or fillable. |
| [setFlattenLayers](#setFlattenLayers-boolean-) | Sets the option to flatten the layers in the PDF document. When enabled, all layers in the document are merged into a single layer, removing their separate structure. This option is useful for sanitizing documents by simplifying their content and ensuring no hidden data resides within layers. |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | Sets the document image conversion option. The option must be enabled manually when using the {@code #All()} method if it is required. |
| [setImageDpi](#setImageDpi-int-) | Sets the option to resolve page images during conversion. |
| [setRemoveAnnotations](#setRemoveAnnotations-boolean-) | Sets a value indicating whether to remove annotations from the document. When enabled, all annotations present in the document will be removed during the sanitization process. Redact annotations will be applied. |
| [setRemoveAttachments](#setRemoveAttachments-boolean-) | Sets the option to remove all attached files from the document. When enabled, it ensures that any attachments within the PDF are eliminated during the sanitation process. |
| [setRemoveJavaScriptsAndActions](#setRemoveJavaScriptsAndActions-boolean-) | Sets a value indicating whether JavaScript and associated actions should be removed from the document. This option is useful to eliminate potential security vulnerabilities introduced by embedded scripts. |
| [setRemoveMetadata](#setRemoveMetadata-boolean-) | Sets an option to remove metadata from the document. If set to true, metadata such as document properties and additional embedded metadata information will be removed during sanitization. |
| [setRemoveSearchIndexAndPrivateInfo](#setRemoveSearchIndexAndPrivateInfo-boolean-) | Sets a value indicating whether the search index and private information should be removed from the document. Enables the removal of embedded search indices and private data to enhance document security and privacy. |

### HiddenDataSanitizationOptions {#HiddenDataSanitizationOptions--}
```
public HiddenDataSanitizationOptions()
```



### all {#all--}
```
public static HiddenDataSanitizationOptions all()
```

Creates a new instance of the {@link HiddenDataSanitizationOptions} class with all options set for sanitization. This includes enabling the removal of annotations, JavaScript, metadata, attachments, search index, private information, flattening of forms and layers, while disabling the option to convert pages to images. Optional configurations like {@code ImageCompressionOptions}({@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}) or {@code ConvertPagesToImages}({@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}) can be manually modified after obtaining the instance, as they are not active by default.

**Returns:**
A {@link HiddenDataSanitizationOptions} instance with all sanitization options preconfigured.

### getConvertPagesToImages {#getConvertPagesToImages--}
```
public final boolean getConvertPagesToImages()
```

Gets the option to convert pages to images. If this option is enabled, the ImageCompressionOptions option will be ignored. The option must be enabled manually when using the {@code #All()} method if it is required. The conversion of pages to images will occur after clearing the main hidden data, which is controlled by other options.

**Returns:**
the option to convert pages to images.

### getFlattenForms {#getFlattenForms--}
```
public final boolean getFlattenForms()
```

Gets a value indicating whether forms in the document should be flattened during the sanitization process. Flattening forms converts interactive form fields into static content, making them non-editable or fillable.

**Returns:**
a value indicating whether forms in the document should be flattened during the sanitization process.

### getFlattenLayers {#getFlattenLayers--}
```
public final boolean getFlattenLayers()
```

Gets the option to flatten the layers in the PDF document. When enabled, all layers in the document are merged into a single layer, removing their separate structure. This option is useful for sanitizing documents by simplifying their content and ensuring no hidden data resides within layers.

**Returns:**
the option to flatten the layers in the PDF document.

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

Gets the document image conversion option. The option must be enabled manually when using the {@code #All()} method if it is required.

**Returns:**
the document image conversion option.

### getImageDpi {#getImageDpi--}
```
public final int getImageDpi()
```

Gets the option to resolve page images during conversion.

**Returns:**
the option to resolve page images during conversion.

### getRemoveAnnotations {#getRemoveAnnotations--}
```
public final boolean getRemoveAnnotations()
```

Gets a value indicating whether to remove annotations from the document. When enabled, all annotations present in the document will be removed during the sanitization process. Redact annotations will be applied.

**Returns:**
a value indicating whether to remove annotations from the document.

### getRemoveAttachments {#getRemoveAttachments--}
```
public final boolean getRemoveAttachments()
```

Gets the option to remove all attached files from the document. When enabled, it ensures that any attachments within the PDF are eliminated during the sanitation process.

**Returns:**
the option to remove all attached files from the document.

### getRemoveJavaScriptsAndActions {#getRemoveJavaScriptsAndActions--}
```
public final boolean getRemoveJavaScriptsAndActions()
```

Gets a value indicating whether JavaScript and associated actions should be removed from the document. This option is useful to eliminate potential security vulnerabilities introduced by embedded scripts.

**Returns:**
a value indicating whether JavaScript and associated actions should be removed from the document.

### getRemoveMetadata {#getRemoveMetadata--}
```
public final boolean getRemoveMetadata()
```

Gets an option to remove metadata from the document. If set to true, metadata such as document properties and additional embedded metadata information will be removed during sanitization.

**Returns:**
an option to remove metadata from the document.

### getRemoveSearchIndexAndPrivateInfo {#getRemoveSearchIndexAndPrivateInfo--}
```
public final boolean getRemoveSearchIndexAndPrivateInfo()
```

Gets a value indicating whether the search index and private information should be removed from the document. Enables the removal of embedded search indices and private data to enhance document security and privacy.

**Returns:**
a value indicating whether the search index and private information should be removed from the document.

### setConvertPagesToImages {#setConvertPagesToImages-boolean-}
```
public final void setConvertPagesToImages(boolean value)
```

Sets the option to convert pages to images. If this option is enabled, the ImageCompressionOptions option will be ignored. The option must be enabled manually when using the {@code #All()} method if it is required. The conversion of pages to images will occur after clearing the main hidden data, which is controlled by other options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | the option to convert pages to images. |

### setFlattenForms {#setFlattenForms-boolean-}
```
public final void setFlattenForms(boolean value)
```

Sets a value indicating whether forms in the document should be flattened during the sanitization process. Flattening forms converts interactive form fields into static content, making them non-editable or fillable.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | a value indicating whether forms in the document should be flattened during the sanitization process. |

### setFlattenLayers {#setFlattenLayers-boolean-}
```
public final void setFlattenLayers(boolean value)
```

Sets the option to flatten the layers in the PDF document. When enabled, all layers in the document are merged into a single layer, removing their separate structure. This option is useful for sanitizing documents by simplifying their content and ensuring no hidden data resides within layers.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | the option to flatten the layers in the PDF document. |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
Sets the document image conversion option. The option must be enabled manually when using the {@code #All()} method if it is required.

### setImageDpi {#setImageDpi-int-}
```
public final void setImageDpi(int value)
```

Sets the option to resolve page images during conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | the option to resolve page images during conversion. |

### setRemoveAnnotations {#setRemoveAnnotations-boolean-}
```
public final void setRemoveAnnotations(boolean value)
```

Sets a value indicating whether to remove annotations from the document. When enabled, all annotations present in the document will be removed during the sanitization process. Redact annotations will be applied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | a value indicating whether to remove annotations from the document. |

### setRemoveAttachments {#setRemoveAttachments-boolean-}
```
public final void setRemoveAttachments(boolean value)
```

Sets the option to remove all attached files from the document. When enabled, it ensures that any attachments within the PDF are eliminated during the sanitation process.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | the option to remove all attached files from the document. |

### setRemoveJavaScriptsAndActions {#setRemoveJavaScriptsAndActions-boolean-}
```
public final void setRemoveJavaScriptsAndActions(boolean value)
```

Sets a value indicating whether JavaScript and associated actions should be removed from the document. This option is useful to eliminate potential security vulnerabilities introduced by embedded scripts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | a value indicating whether JavaScript and associated actions should be removed from the document. |

### setRemoveMetadata {#setRemoveMetadata-boolean-}
```
public final void setRemoveMetadata(boolean value)
```

Sets an option to remove metadata from the document. If set to true, metadata such as document properties and additional embedded metadata information will be removed during sanitization.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | an option to remove metadata from the document. |

### setRemoveSearchIndexAndPrivateInfo {#setRemoveSearchIndexAndPrivateInfo-boolean-}
```
public final void setRemoveSearchIndexAndPrivateInfo(boolean value)
```

Sets a value indicating whether the search index and private information should be removed from the document. Enables the removal of embedded search indices and private data to enhance document security and privacy.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | a value indicating whether the search index and private information should be removed from the document. |
