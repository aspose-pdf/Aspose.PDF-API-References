---
title: "SaveDoc"
second_title: Aspose.PDF for Go via C++
description: "Convert and save the previously opened PDF-document as Doc-document."
type: docs
url: /go-cpp/convert/savedoc/
---

_Convert and save the previously opened PDF-document as Doc-document._

```go
func (document *Document) SaveDoc(filename string) error
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
	// SaveDoc(filename string) saves previously opened PDF-document as Doc-document with filename
	err = pdf.SaveDoc("sample.doc")
	if err != nil {
		log.Fatal(err)
	}
}
```
