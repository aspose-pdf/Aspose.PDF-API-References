---
title: "SaveDocXEnhanced"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "以前に開いた PDF ドキュメントを 強化認識モード（完全に編集可能な表と段落）付きの DocX ドキュメントとして変換して保存します。"
type: docs
url: /ja/go-cpp/convert/savedocxenhanced/
---

_以前に開いた PDF-document を、拡張認識モード（テーブルと段落を完全に編集可能）で DocX-document として変換して保存します._

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
	// Open(filename string) は、指定したファイル名の PDF-document を開きます
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() は、PDF-document に割り当てられたリソースを解放します
	defer pdf.Close()
	// SaveDocX(filename string) は、以前に開いた PDF-document を拡張認識モードの DocX-document として、指定したファイル名で保存します
	err = pdf.SaveDocXEnhanced("sampleEnhanced.docx")
	if err != nil {
		log.Fatal(err)
	}
}
```
