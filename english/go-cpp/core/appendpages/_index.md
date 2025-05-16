---
title: "AppendPages"
second_title: Aspose.PDF for Go via C++
description: "Append selected pages from another PDF-document."
type: docs
url: /go-cpp/core/appendpages/
---

_Append selected pages from another PDF-document._

```go
func (document *Document) AppendPages(anotherdocument *Document, pagerange string) error
```

**Parameters**: 
  * **anotherdocument** - reference to PDF-document instance
  * **pagerange** - string that specifies which pages to append. Supports individual pages, ranges, and open-ended intervals. For example: "1,3,5", "2-4", "-3", "4-", or "-" for all pages

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) opens a PDF-document with filename
	pdf, err := asposepdf.Open("sample1page.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf.Close()
	// Open(filename string) opens another PDF-document with filename
	anotherpdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer anotherpdf.Close()
	// AppendPages(anotherdocument *Document, pagerange string) appends specific pages from another PDF-document.
	err = pdf.AppendPages(anotherpdf, "1,3")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) saves previously opened PDF-document with new filename
	err = pdf.SaveAs("sample_AppendPages.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
