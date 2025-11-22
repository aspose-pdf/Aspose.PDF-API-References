---
title: "SaveDocXEnhanced"
second_title: Aspose.PDF for Go via C++
description: "Convert and save the previously opened PDF-document as DocX-document with Enhanced Recognition Mode (fully editable tables and paragraphs)."
type: docs
url: /go-cpp/convert/savedocxenhanced/
---

_Convert and save the previously opened PDF-document as DocX-document with Enhanced Recognition Mode (fully editable tables and paragraphs)._

```go
func (document *Document) SaveDocXEnhanced(filename string) error
```

**Parameters**: 
  * **filename** - new filename

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) opens a PDF-document with filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf.Close()
	// SaveDocX(filename string) saves previously opened PDF-document as Enhanced Recognition Mode DocX-document with filename
	err = pdf.SaveDocXEnhanced("sampleEnhanced.docx")
	if err != nil {
		log.Fatal(err)
	}
}
```
