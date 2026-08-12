---
title: "SetMetaInfo"
second_title: "Aspose.PDF for Go via C++"
description: "PDF-dokümanının meta bilgi değerini ayarla."
type: docs
url: /tr/go-cpp/core/setmetainfo/
---

_PDF-dokümanının meta bilgi değerini ayarla._

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
	// Open(filename string) dosya adıyla bir PDF-belgesi açar
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()
	// SetMetaInfo(key, value string) PDF-dokümanının meta bilgi değerini ayarlar
	err = pdf.SetMetaInfo("Author", "Aspose")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
	err = pdf.SaveAs("sample_SetMetaInfo.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
