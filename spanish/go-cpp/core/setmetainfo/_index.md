---
title: "SetMetaInfo"
second_title: "Aspose.PDF para Go vía C++"
description: "Establece el valor de la información meta del documento PDF."
type: docs
url: /es/go-cpp/core/setmetainfo/
---

_Establece el valor de la información meta del documento PDF._

```go
func (document *Document) SetMetaInfo(key, value string) error
```

**Parameters**: 
  * **key** - key whose value to set
  * **value** - value to be set

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// SetMetaInfo(key, value string) establece el valor de la información meta del documento PDF
	err = pdf.SetMetaInfo("Author", "Aspose")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_SetMetaInfo.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
