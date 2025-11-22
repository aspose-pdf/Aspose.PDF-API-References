---
title: "SaveBooklet"
second_title: Aspose.PDF for Go via C++
description: "Convert and save the previously opened PDF-document as booklet PDF-document."
type: docs
url: /go-cpp/convert/savebooklet/
---

_Convert and save the previously opened PDF-document as booklet PDF-document._

```go
func (document *Document) SaveBooklet(filename string) error
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
	// SaveBooklet(filename string) saves previously opened PDF-document as booklet PDF-document with filename
	err = pdf.SaveBooklet("sample_Booklet.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
