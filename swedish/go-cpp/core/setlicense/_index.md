---
title: "SetLicense"
second_title: "Aspose.PDF för Go via C++"
description: "Ställ in licens med filnamn."
type: docs
url: /sv/go-cpp/core/setlicense/
---

_Ställ in licens med filnamn._

```go
func (document *Document) SetLicense(filename string) error
```

**Parameters**: 
  * **filename** - full name of the license file

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
	// SetLicense(filename string) licensierar med filnamn
	err = pdf.SetLicense("Aspose.PDF.GoViaCPP.lic")
	if err != nil {
		log.Fatal(err)
	}
	// Arbeta med PDF-dokument
	// ...
}
```
