---
title: "SetLicense"
second_title: "Aspose.PDF untuk Go via C++"
description: "Atur lisensi dengan nama file."
type: docs
url: /id/go-cpp/core/setlicense/
---

_Set lisensi dengan nama file._

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
	// Open(filename string) membuka PDF-dokumen dengan nama file
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
	defer pdf.Close()
	// SetLicense(filename string) melisensikan dengan nama file
	err = pdf.SetLicense("Aspose.PDF.GoViaCPP.lic")
	if err != nil {
		log.Fatal(err)
	}
	// Bekerja dengan PDF-document
	// ...
}
```
