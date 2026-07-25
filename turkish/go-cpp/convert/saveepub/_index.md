---
title: "SaveEpub"
second_title: "Aspose.PDF for Go via C++"
description: "Önceden açılmış PDF-dokümanını Epub-dokümanı olarak dönüştür ve kaydet."
type: docs
url: /tr/go-cpp/convert/saveepub/
---

_Dönüştür ve daha önce açılmış PDF-belgesini Epub-belgesi olarak kaydet._

```go
func (document *Document) SaveEpub(filename string) error
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
	// SaveEpub(filename string) daha önce açılmış PDF-belgesini Epub-belgesi olarak dosya adıyla kaydeder
	err = pdf.SaveEpub("sample.epub")
	if err != nil {
		log.Fatal(err)
	}
}
```
