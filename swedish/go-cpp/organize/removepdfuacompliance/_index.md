---
title: "RemovePdfUaCompliance"
second_title: "Aspose.PDF för Go via C++"
description: "Ta bort PDF/UA-efterlevnad från ett PDF-dokument."
type: docs
url: /sv/go-cpp/organize/removepdfuacompliance/
---

_Ta bort PDF/UA-efterlevnad från ett PDF-dokument._

```go
func (document *Document) RemovePdfUaCompliance() error
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
	// RemovePdfUaCompliance() tar bort PDF/UA-efterlevnad från PDF-dokument
	err = pdf.RemovePdfUaCompliance()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
	err = pdf.SaveAs("sample_RemovePdfUaCompliance.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
