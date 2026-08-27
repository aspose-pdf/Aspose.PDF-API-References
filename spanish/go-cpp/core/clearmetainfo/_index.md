---
title: "ClearMetaInfo"
second_title: "Aspose.PDF para Go vía C++"
description: "Elimina todos los valores de metainformación del documento PDF."
type: docs
url: /es/go-cpp/core/clearmetainfo/
---

_Elimina todos los valores de metainformación del documento PDF._

```go
func (document *Document) ClearMetaInfo() error
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
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// ClearMetaInfo() elimina todos los valores de metainformación del documento PDF
	err = pdf.ClearMetaInfo()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_ClearMetaInfo.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
