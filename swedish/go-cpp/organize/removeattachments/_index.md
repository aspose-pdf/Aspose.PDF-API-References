---
title: "RemoveAttachments"
second_title: "Aspose.PDF för Go via C++"
description: "Ta bort bilagor från PDF-dokument."
type: docs
url: /sv/go-cpp/organize/removeattachments/
---

_Ta bort bilagor från PDF-dokument._

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
	// Open(filename string) öppnar ett PDF-dokument med filnamn
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf.Close()
	// RemoveAttachments() tar bort bilagor från PDF-dokument
	err = pdf.RemoveAttachments()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
	err = pdf.SaveAs("sample_RemoveAttachments.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
