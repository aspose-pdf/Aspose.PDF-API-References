---
title: "SaveDocX"
second_title: "Aspose.PDF for Go via C++"
description: "Önceden açılmış PDF-dokümanını DocX-dokümanı olarak dönüştür ve kaydet."
type: docs
url: /tr/go-cpp/convert/savedocx/
---

_Daha önce açılmış PDF-dokümanı DocX-dokümanı olarak dönüştür ve kaydet._

```go
func (document *Document) SaveDocX(filename string) error
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
	// SaveDocX(filename string) daha önce açılmış PDF-dokümanı DocX-dokümanı olarak dosya adıyla kaydeder
	err = pdf.SaveDocX("sample.docx")
	if err != nil {
		log.Fatal(err)
	}
}
```
