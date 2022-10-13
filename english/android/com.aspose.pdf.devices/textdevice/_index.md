---
title: TextDevice
second_title: Aspose.PDF for Java API Reference
description: Represents class for converting pdf document pages into text.
type: docs
weight: 26
url: /java/com.aspose.pdf.devices/textdevice/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device), [com.aspose.pdf.devices.PageDevice](../../com.aspose.pdf.devices/pagedevice)
```
public final class TextDevice extends PageDevice
```

Represents class for converting pdf document pages into text.

--------------------

> ```
> The example demonstrates how to extract text on the first PDF document page.
>   
> 	       Document doc = new Document(inFile);
> 	       String extractedText;
> 	       ByteArrayOutputStream ms = new ByteArrayOutputStream();
> 	       try 
> 	       {
> 	           // create text device
> 	           TextDevice device = new TextDevice();
> 	           // convert the page and save text to the stream
> 	           device.process(doc.getPages().get_Item(1), ms);
> 	           // use the extracted text	           
> 	           extractedText = Encoding.getUnicode().getString(ms.toByteArray());
> 	           
> 		    ms.close();
> 		} catch (IOException e) {
> 		    e.printStackTrace();
> 		}
> ```

--------------------

The  TextDevice  object is basically used to extract text from pdf page.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextDevice(TextExtractionOptions extractionOptions)](#TextDevice-com.aspose.pdf.TextExtractionOptions-) | Initializes a new instance of the  TextDevice  with text extraction options. |
| [TextDevice()](#TextDevice--) | Initializes a new instance of the  TextDevice  with the Raw text formatting mode and Unicode text encoding. |
| [TextDevice(TextEncodingInternal encoding)](#TextDevice-com.aspose.pdf.TextEncodingInternal-) | Initializes a new instance of the  TextDevice  for the specified encoding. |
| [TextDevice(Charset encoding)](#TextDevice-java.nio.charset.Charset-) |  |
| [TextDevice(TextExtractionOptions extractionOptions, TextEncodingInternal encoding)](#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-) | Initializes a new instance of the  TextDevice  for the specified encoding with text extraction options. |
| [TextDevice(TextExtractionOptions extractionOptions, Charset encoding)](#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getExtractionOptions()](#getExtractionOptions--) | Gets or sets text extraction options. |
| [setExtractionOptions(TextExtractionOptions value)](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) |  |
| [getEncodingInternal()](#getEncodingInternal--) | Gets or sets encoding of extracted text. |
| [setEncodingInternal(TextEncodingInternal value)](#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-) | Sets encoding of extracted text. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Sets encoding of extracted text. |
| [processInternal(Page page, System.IO.Stream output)](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Convert page and save it as text stream. |
| [process(Page page, OutputStream output)](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Convert page and save it as text stream. |
### TextDevice(TextExtractionOptions extractionOptions) {#TextDevice-com.aspose.pdf.TextExtractionOptions-}
```
public TextDevice(TextExtractionOptions extractionOptions)
```


Initializes a new instance of the  TextDevice  with text extraction options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extractionOptions | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | Text extraction options. |

### TextDevice() {#TextDevice--}
```
public TextDevice()
```


Initializes a new instance of the  TextDevice  with the Raw text formatting mode and Unicode text encoding.

### TextDevice(TextEncodingInternal encoding) {#TextDevice-com.aspose.pdf.TextEncodingInternal-}
```
public TextDevice(TextEncodingInternal encoding)
```


Initializes a new instance of the  TextDevice  for the specified encoding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encoding | [TextEncodingInternal](../../com.aspose.pdf/textencodinginternal) | Encoding of extracted text |

### TextDevice(Charset encoding) {#TextDevice-java.nio.charset.Charset-}
```
public TextDevice(Charset encoding)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encoding | java.nio.charset.Charset |  |

### TextDevice(TextExtractionOptions extractionOptions, TextEncodingInternal encoding) {#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-}
```
public TextDevice(TextExtractionOptions extractionOptions, TextEncodingInternal encoding)
```


Initializes a new instance of the  TextDevice  for the specified encoding with text extraction options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extractionOptions | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | Text extraction options. |
| encoding | [TextEncodingInternal](../../com.aspose.pdf/textencodinginternal) | Encoding of extracted text. |

### TextDevice(TextExtractionOptions extractionOptions, Charset encoding) {#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-}
```
public TextDevice(TextExtractionOptions extractionOptions, Charset encoding)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extractionOptions | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) |  |
| encoding | java.nio.charset.Charset |  |

### getExtractionOptions() {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```


Gets or sets text extraction options.

--------------------

> ```
> The example demonstrates how to extracted text in raw order.
>   
> 	       Document doc = new Document(inFile);
> 	       String extractedText;
> 	       // create text device
> 	       TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));
> 	       // convert the page and save text to the stream
> 	       device.process(doc.getPages().get_Item(1), outFile);
> ```

**Returns:**
[TextExtractionOptions](../../com.aspose.pdf/textextractionoptions)
### setExtractionOptions(TextExtractionOptions value) {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
```
public void setExtractionOptions(TextExtractionOptions value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) |  |

### getEncodingInternal() {#getEncodingInternal--}
```
public TextEncodingInternal getEncodingInternal()
```


Gets or sets encoding of extracted text.

--------------------

> ```
> The example demonstrates how to represent extracted text in UTF-8 encoding.
>   
> 	       Document doc = new Document(inFile);
> 	       String extractedText;
> 	       // create text device
> 	       TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8"));
> 	       // convert the page and save text to the stream
> 	       device.process(doc.getPages().get_Item(1), outFile);
> ```

**Returns:**
[TextEncodingInternal](../../com.aspose.pdf/textencodinginternal)
### setEncodingInternal(TextEncodingInternal value) {#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-}
```
public void setEncodingInternal(TextEncodingInternal value)
```


Sets encoding of extracted text.

--------------------

> ```
> The example demonstrates how to represent extracted text in UTF-8 encoding.
>   
> 		       Document doc = new Document(inFile);
> 		       String extractedText;
> 		       // create text device
> 		       TextDevice device = new TextDevice(TextEncodingInternal.getUTF8());
> 		       // convert the page and save text to the stream
> 		       device.process(doc.getPages().get_Item(1), outFile);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextEncodingInternal](../../com.aspose.pdf/textencodinginternal) |  |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Sets encoding of extracted text.

--------------------

> ```
> The example demonstrates how to represent extracted text in UTF-8 encoding.
>   
> 		       Document doc = new Document(inFile);
> 		       String extractedText;
> 		       // create text device
> 		       TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8"));
> 		       // convert the page and save text to the stream
> 		       device.process(doc.getPages().get_Item(1), outFile);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### processInternal(Page page, System.IO.Stream output) {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(Page page, System.IO.Stream output)
```


Convert page and save it as text stream.

--------------------

> ```
> The example demonstrates how to extract text on the first PDF document page.
>   
> 	       Document doc = new Document(inFile);
> 	       String extractedText;
> 	       ByteArrayOutputStream ms = new ByteArrayOutputStream();
> 	       
> 	           // create text device
> 	           TextDevice device = new TextDevice();
> 	           // convert the page and save text to the stream
> 	           device.process(doc.getPages().get_Item(1), ms);
> 	           // use the extracted text
> 	           extractedText = Encoding.getUnicode().getString(ms.toByteArray());
> 	           ms.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to convert. |
| output | com.aspose.ms.System.IO.Stream | Result stream. |

### process(Page page, OutputStream output) {#process-com.aspose.pdf.Page-java.io.OutputStream-}
```
public void process(Page page, OutputStream output)
```


Convert page and save it as text stream.

--------------------

> ```
> The example demonstrates how to extract text on the first PDF document page.
>   
> 	       Document doc = new Document(inFile);
> 	       String extractedText;
> 	       ByteArrayOutputStream ms = new ByteArrayOutputStream();
> 	       
> 	           // create text device
> 	           TextDevice device = new TextDevice();
> 	           // convert the page and save text to the stream
> 	           device.process(doc.getPages().get_Item(1), ms);
> 	           // use the extracted text
> 	           extractedText = Encoding.getUnicode().getString(ms.toByteArray());
> 	           ms.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to convert. |
| output | java.io.OutputStream | Result stream. |

