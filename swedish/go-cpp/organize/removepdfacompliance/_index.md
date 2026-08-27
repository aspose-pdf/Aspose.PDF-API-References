---
title: "RemovePdfaCompliance"
second_title: "Aspose.PDF för Go via C++"
description: "Ta bort PDF/A-efterlevnad från ett PDF-dokument."
type: docs
url: /sv/go-cpp/organize/removepdfacompliance/
---

_Ta bort PDF/A-efterlevnad från ett PDF-dokument._

```go
func (document *Document) RemovePdfaCompliance() error
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
	// RemovePdfaCompliance() tar bort PDF/A-efterlevnad från PDF-dokument
	err = pdf.RemovePdfaCompliance()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
	err = pdf.SaveAs("sample_RemovePdfaCompliance.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
