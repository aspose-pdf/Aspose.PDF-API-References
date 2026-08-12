---
title: "add_text_header"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dökümanının Başlığında metin ekler."
type: docs
url: /tr/rust-cpp/organize/add_text_header/
---

_PDF-dökümanının Başlığında metin ekler._

```rust
pub fn add_text_header(&self, header: &str) -> Result<(), PdfError>
```

**Arguments**
  * **header** - the pages header

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // PDF-dokümanının başlığına metin ekle
    pdf.add_text_header("HEADER")?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_add_text_header.pdf")?;

    Ok(())
}

```