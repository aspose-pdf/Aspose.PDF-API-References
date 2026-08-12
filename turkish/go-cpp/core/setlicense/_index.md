---
title: "SetLicense"
second_title: "Aspose.PDF for Go via C++"
description: "Dosya adıyla lisansı ayarla."
type: docs
url: /tr/go-cpp/core/setlicense/
---

_Lisansı dosya adıyla ayarla._

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
	// Open(filename string) dosya adıyla bir PDF-belgesi açar
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()
	// SetLicense(filename string) lisansları dosya adıyla ayarlar
	err = pdf.SetLicense("Aspose.PDF.GoViaCPP.lic")
	if err != nil {
		log.Fatal(err)
	}
	// PDF-dokümanıyla çalışmak
	// ...
}
```
