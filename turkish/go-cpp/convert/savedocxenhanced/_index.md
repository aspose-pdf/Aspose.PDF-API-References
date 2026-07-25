---
title: "SaveDocXEnhanced"
second_title: "Aspose.PDF for Go via C++"
description: "Önceden açılmış PDF-dokümanını Gelişmiş Tanıma Modu ile DocX-dokümanı olarak dönüştür ve kaydet (tamamen düzenlenebilir tablolar ve paragraflar)."
type: docs
url: /tr/go-cpp/convert/savedocxenhanced/
---

_Önceden açılmış PDF-belgesini Gelişmiş Tanıma Modu ile DocX-belgesi olarak dönüştür ve kaydet (tamamen düzenlenebilir tablolar ve paragraflar)._

```go
func (document *Document) SaveDocXEnhanced(filename string) error
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
	// SaveDocX(filename string) önceden açılmış PDF-belgesini dosya adıyla Gelişmiş Tanıma Modu DocX-belgesi olarak kaydeder
	err = pdf.SaveDocXEnhanced("sampleEnhanced.docx")
	if err != nil {
		log.Fatal(err)
	}
}
```
