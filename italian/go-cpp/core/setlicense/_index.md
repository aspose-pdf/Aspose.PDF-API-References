---
title: "SetLicense"
second_title: "Aspose.PDF per Go via C++"
description: "Imposta la licenza con nome file."
type: docs
url: /it/go-cpp/core/setlicense/
---

_Imposta la licenza con nome file._

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
	// Open(filename string) apre un PDF-document con filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf.Close()
	// SetLicense(filename string) assegna la licenza con nome file
	err = pdf.SetLicense("Aspose.PDF.GoViaCPP.lic")
	if err != nil {
		log.Fatal(err)
	}
	// Lavorare con PDF-document
	// ...
}
```
