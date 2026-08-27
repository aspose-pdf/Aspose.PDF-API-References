---
title: "Repair"
second_title: "Aspose.PDF för Go via C++"
description: "Reparera PDF-dokument."
type: docs
url: /sv/go-cpp/organize/repair/
---

_Reparera PDF-dokumentet._

```go
func (document *Document) Repair() error
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
	// Repair() reparerar PDF-dokumentet
	err = pdf.Repair()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
	err = pdf.SaveAs("sample_Repair.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
