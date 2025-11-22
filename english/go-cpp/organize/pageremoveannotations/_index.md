---
title: "PageRemoveAnnotations"
second_title: Aspose.PDF for Go via C++
description: "Remove annotations in page."
type: docs
url: /go-cpp/organize/pageremoveannotations/
---

_Remove annotations in page._

```go
func (document *Document) PageRemoveAnnotations(num int32) error
```

**Parameters**: 
  * **num** - page number of the PDF-document

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
	// PageRemoveAnnotations(num int32) removes annotations in page
	err = pdf.PageRemoveAnnotations(1)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) saves previously opened PDF-document with new filename
	err = pdf.SaveAs("sample_page1_RemoveAnnotations.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
