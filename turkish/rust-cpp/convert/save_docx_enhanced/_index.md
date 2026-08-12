---
title: "save_docx_enhanced"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Daha önce açılmış PDF-dokümanını Gelişmiş Tanıma Modu ile DOCX-dokümanı olarak dönüştürür ve kaydeder (tamamen düzenlenebilir tablolar ve paragraflar)."
type: docs
url: /tr/rust-cpp/convert/save_docx_enhanced/
---

_Daha önce açılmış PDF-dokümanını Gelişmiş Tanıma Modu ile DOCX-dokümanı olarak dönüştürür ve kaydeder (tamamen düzenlenebilir tablolar ve paragraflar)._

```rust
pub fn save_docx_enhanced(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // Daha önce açılmış PDF-dokümanını Gelişmiş Tanıma Modu ile DOCX-dokümanı olarak dönüştür ve kaydet (tamamen düzenlenebilir tablolar ve paragraflar)
    pdf.save_docx_enhanced("sample_enhanced.docx")?;

    Ok(())
}

```