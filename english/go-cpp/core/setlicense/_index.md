---
title: "SetLicense"
second_title: Aspose.PDF for Go via C++
description: "Set license with filename."
type: docs
url: /go-cpp/core/setlicense/
---

_Set license with filename._

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
	// Open(filename string) opens a PDF-document with filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf.Close()
	// SetLicense(filename string) licenses with filename
	err = pdf.SetLicense("Aspose.PDF.GoViaCPP.lic")
	if err != nil {
		log.Fatal(err)
	}
	// Working with PDF-document
	// ...
}
```
