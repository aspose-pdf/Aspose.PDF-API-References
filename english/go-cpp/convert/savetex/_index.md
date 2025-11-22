---
title: "SaveTeX"
second_title: Aspose.PDF for Go via C++
description: "Convert and save the previously opened PDF-document as TeX-document."
type: docs
url: /go-cpp/convert/savetex/
---

_Convert and save the previously opened PDF-document as TeX-document._

```go
func (document *Document) SaveTeX(filename string) error
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
	// SaveTeX(filename string) saves previously opened PDF-document as TeX-document with filename
	err = pdf.SaveTeX("sample.tex")
	if err != nil {
		log.Fatal(err)
	}
}
```
