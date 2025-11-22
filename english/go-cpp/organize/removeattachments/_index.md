---
title: "RemoveAttachments"
second_title: Aspose.PDF for Go via C++
description: "Remove attachments from PDF-document."
type: docs
url: /go-cpp/organize/removeattachments/
---

_Remove attachments from PDF-document._

```go
func (document *Document) RemoveAttachments() error
```

**Parameters**: 

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
	// RemoveAttachments() removes attachments from PDF-document
	err = pdf.RemoveAttachments()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) saves previously opened PDF-document with new filename
	err = pdf.SaveAs("sample_RemoveAttachments.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
