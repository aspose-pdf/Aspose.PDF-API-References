---
title: "PageRemoveAnnotations"
second_title: "Aspose.PDF för Go via C++"
description: "Ta bort annotationer på sidan."
type: docs
url: /sv/go-cpp/organize/pageremoveannotations/
---

_Ta bort annotationer på sidan._

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
	// Open(filename string) öppnar ett PDF-dokument med filnamn
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf.Close()
	// PageRemoveAnnotations(num int32) tar bort annotationer på sidan
	err = pdf.PageRemoveAnnotations(1)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
	err = pdf.SaveAs("sample_page1_RemoveAnnotations.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
