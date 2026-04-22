---
title: "RemoveSigns"
second_title: Aspose.PDF for Go via C++
description: "Remove signs from PDF-document."
type: docs
url: /go-cpp/security/removesigns/
---

_Remove signs from PDF-document._

```go
func (document *Document) RemoveSigns(filename string) error
```

**Parameters**: 
  * **filename** - new filename, without signs

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) opens a PDF-document with filename
	pdf, err := asposepdf.Open("sample_with_sign.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf.Close()
	// RemoveSigns(filename string) removes signs from PDF-document
	err = pdf.RemoveSigns("sample_RemoveSigns.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
