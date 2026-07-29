---
title: "OptimizeResource"
second_title: "Aspose.PDF för Go via C++"
description: "Optimera resurserna i PDF-dokumentet."
type: docs
url: /sv/go-cpp/organize/optimizeresource/
---

_Optimera resurser i PDF-dokumentet._

```go
func (document *Document) OptimizeResource() error
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
	// OptimizeResource() optimerar resurser i PDF-dokumentet
	err = pdf.OptimizeResource()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
	err = pdf.SaveAs("sample_OptimizeResource.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
