---
title: "SetBackground"
second_title: "Aspose.PDF for Go via C++"
description: "PDF belgesi arka plan rengini ayarla."
type: docs
url: /tr/go-cpp/organize/setbackground/
---

_PDF-dokümanının arka plan rengini ayarla._

```go
func (document *Document) SetBackground(r, g, b int32) error
```

**Parameters**: 
  * **r** - Red color of RGB color model (0-255)
  * **g** - Green color of RGB color model (0-255)
  * **b** - Blue color of RGB color model (0-255)

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
	// SetBackground(r, g, b int32) PDF-dokümanının arka plan rengini ayarlar
	err = pdf.SetBackground(200, 100, 101)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
	err = pdf.SaveAs("sample_SetBackground.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
