---
title: "SaveXlsX"
second_title: "Aspose.PDF for Go via C++"
description: "Önceden açılmış PDF-dokümanını XlsX-dokümanı olarak dönüştür ve kaydet."
type: docs
url: /tr/go-cpp/convert/savexlsx/
---

_Önceden açılmış PDF-belgesini XlsX-belgesi olarak dönüştür ve kaydet._

```go
func (document *Document) SaveXlsX(filename string) error
```

**Parameters**: 
  * **filename** - new filename

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
	// SaveXlsX(filename string) önceden açılmış PDF-belgesini dosya adıyla XlsX-belgesi olarak kaydeder
	err = pdf.SaveXlsX("sample.xlsx")
	if err != nil {
		log.Fatal(err)
	}
}
```
