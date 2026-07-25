---
title: "SaveXps"
second_title: "Aspose.PDF for Go via C++"
description: "Önceden açılmış PDF-dokümanını Xps-dokümanı olarak dönüştür ve kaydet."
type: docs
url: /tr/go-cpp/convert/savexps/
---

_Dönüştür ve daha önce açılmış PDF-belgesini Xps-belgesi olarak kaydet._

```go
func (document *Document) SaveXps(filename string) error
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
	// SaveXps(filename string) daha önce açılmış PDF-belgesini Xps-belgesi olarak dosya adıyla kaydeder
	err = pdf.SaveXps("sample.xps")
	if err != nil {
		log.Fatal(err)
	}
}
```
