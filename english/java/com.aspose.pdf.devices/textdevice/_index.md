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

```
The example demonstrates how to extract text on the first PDF document page.
 
	       Document doc = new Document(inFile);
	       String extractedText;
	       ByteArrayOutputStream ms = new ByteArrayOutputStream();
	       try 
	       {
	           // create text device
	           TextDevice device = new TextDevice();
	           // convert the page and save text to the stream
	           device.process(doc.getPages().get_Item(1), ms);
	           // use the extracted text	           
	           extractedText = Encoding.getUnicode().getString(ms.toByteArray());
	           
		    ms.close();
		} catch (IOException e) {
		    e.printStackTrace();
		}
```

--------------------

The  TextDevice  object is basically used to extract text from pdf page.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextDevice(TextExtractionOptions extractionOptions)](#TextDevice-com.aspose.pdf.TextExtractionOptions-) | Initializes a new instance of the  TextDevice  with text extraction options. |
| [TextDevice()](#TextDevice--) | Initializes a new instance of the  TextDevice  with the Raw text formatting mode and Unicode text encoding. |
| [TextDevice(TextEncodingInternal encoding)](#TextDevice-com.aspose.pdf.TextEncodingInternal-) | Initializes a new instance of the  TextDevice  for the specified encoding. |
| [TextDevice(Charset encoding)](#TextDevice-java.nio.charset.Charset-) | Initializes a new instance of the  TextDevice  for the specified encoding. |
| [TextDevice(TextExtractionOptions extractionOptions, TextEncodingInternal encoding)](#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-) | Initializes a new instance of the  TextDevice  for the specified encoding with text extraction options. |
| [TextDevice(TextExtractionOptions extractionOptions, Charset encoding)](#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-) | Initializes a new instance of the  TextDevice  for the specified encoding with text extraction options. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | Gets encoding of extracted text. |
| [getEncodingInternal()](#getEncodingInternal--) | Gets encoding of extracted text. |
| [getExtractionOptions()](#getExtractionOptions--) | Gets text extraction options. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [process(Page page, System.Drawing.Graphics gr)](#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-) | Renders page on the graphics |
| [process(Page page, OutputStream output)](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Convert page and save it as text stream. |
| [process(Page page, String outputFileName)](#process-com.aspose.pdf.Page-java.lang.String-) | Performs some operation on the given page and saves results into the file. |
| [processInternal(Page page, System.IO.Stream output)](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Convert page and save it as text stream. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Sets encoding of extracted text. |
| [setEncodingInternal(TextEncodingInternal value)](#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-) | Sets encoding of extracted text. |
| [setExtractionOptions(TextExtractionOptions value)](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | Sets text extraction options. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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


Initializes a new instance of the  TextDevice  for the specified encoding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encoding | java.nio.charset.Charset | Encoding of extracted text |

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


Initializes a new instance of the  TextDevice  for the specified encoding with text extraction options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extractionOptions | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | Text extraction options. |
| encoding | java.nio.charset.Charset | Encoding of extracted text. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Gets encoding of extracted text.

**Returns:**
java.nio.charset.Charset - Charset element

--------------------

```
The example demonstrates how to represent extracted text in UTF-8 encoding.
 
	       Document doc = new Document(inFile);
	       String extractedText;
	       // create text device
	       TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8"));
	       // convert the page and save text to the stream
	       device.process(doc.getPages().get_Item(1), outFile);
```
### getEncodingInternal() {#getEncodingInternal--}
```
public TextEncodingInternal getEncodingInternal()
```


Gets encoding of extracted text.

**Returns:**
[TextEncodingInternal](../../com.aspose.pdf/textencodinginternal) - TextEncodingInternal element

--------------------

```
The example demonstrates how to represent extracted text in UTF-8 encoding.
 
	       Document doc = new Document(inFile);
	       String extractedText;
	       // create text device
	       TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8"));
	       // convert the page and save text to the stream
	       device.process(doc.getPages().get_Item(1), outFile);
```
### getExtractionOptions() {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```


Gets text extraction options.

**Returns:**
[TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) - TextExtractionOptions element

--------------------

```
The example demonstrates how to extracted text in raw order.
 
	       Document doc = new Document(inFile);
	       String extractedText;
	       // create text device
	       TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));
	       // convert the page and save text to the stream
	       device.process(doc.getPages().get_Item(1), outFile);
```
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### process(Page page, System.Drawing.Graphics gr) {#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-}
```
public void process(Page page, System.Drawing.Graphics gr)
```


Renders page on the graphics

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page object |
| gr | com.aspose.ms.System.Drawing.Graphics | internal object |

### process(Page page, OutputStream output) {#process-com.aspose.pdf.Page-java.io.OutputStream-}
```
public void process(Page page, OutputStream output)
```


Convert page and save it as text stream.

--------------------

```
The example demonstrates how to extract text on the first PDF document page.
 
	       Document doc = new Document(inFile);
	       String extractedText;
	       ByteArrayOutputStream ms = new ByteArrayOutputStream();
	       
	           // create text device
	           TextDevice device = new TextDevice();
	           // convert the page and save text to the stream
	           device.process(doc.getPages().get_Item(1), ms);
	           // use the extracted text
	           extractedText = Encoding.getUnicode().getString(ms.toByteArray());
	           ms.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to convert. |
| output | java.io.OutputStream | Result stream. |

### process(Page page, String outputFileName) {#process-com.aspose.pdf.Page-java.lang.String-}
```
public void process(Page page, String outputFileName)
```


Performs some operation on the given page and saves results into the file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to process. |
| outputFileName | java.lang.String | This file contains the results of processing. |

### processInternal(Page page, System.IO.Stream output) {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(Page page, System.IO.Stream output)
```


Convert page and save it as text stream.

--------------------

```
The example demonstrates how to extract text on the first PDF document page.
 
	       Document doc = new Document(inFile);
	       String extractedText;
	       ByteArrayOutputStream ms = new ByteArrayOutputStream();
	       
	           // create text device
	           TextDevice device = new TextDevice();
	           // convert the page and save text to the stream
	           device.process(doc.getPages().get_Item(1), ms);
	           // use the extracted text
	           extractedText = Encoding.getUnicode().getString(ms.toByteArray());
	           ms.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to convert. |
| output | com.aspose.ms.System.IO.Stream | Result stream. |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Sets encoding of extracted text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset | Charset element

--------------------

```
The example demonstrates how to represent extracted text in UTF-8 encoding.
 
		       Document doc = new Document(inFile);
		       String extractedText;
		       // create text device
		       TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8"));
		       // convert the page and save text to the stream
		       device.process(doc.getPages().get_Item(1), outFile);
``` |

### setEncodingInternal(TextEncodingInternal value) {#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-}
```
public void setEncodingInternal(TextEncodingInternal value)
```


Sets encoding of extracted text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextEncodingInternal](../../com.aspose.pdf/textencodinginternal) | TextEncodingInternal element

--------------------

```
The example demonstrates how to represent extracted text in UTF-8 encoding.
 
		       Document doc = new Document(inFile);
		       String extractedText;
		       // create text device
		       TextDevice device = new TextDevice(TextEncodingInternal.getUTF8());
		       // convert the page and save text to the stream
		       device.process(doc.getPages().get_Item(1), outFile);
``` |

### setExtractionOptions(TextExtractionOptions value) {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
```
public void setExtractionOptions(TextExtractionOptions value)
```


Sets text extraction options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | TextExtractionOptions element

--------------------

```
The example demonstrates how to extracted text in raw order.
 
	       Document doc = new Document(inFile);
	       String extractedText;
	       // create text device
	       TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));
	       // convert the page and save text to the stream
	       device.process(doc.getPages().get_Item(1), outFile);
``` |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

