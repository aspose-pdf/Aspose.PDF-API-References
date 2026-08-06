---
title: "page_add_text_header"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Sayfa üstbilgisinde metin ekler."
type: docs
url: /tr/rust-cpp/organize/page_add_text_header/
---

_Sayfa üstbilgisinde metin ekler._

```rust
pub fn page_add_text_header(&self, num: i32, header: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // Sayfa başlığına metin ekle
    pdf.page_add_text_header(1, "HEADER")?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_page1_add_text_header.pdf")?;

    Ok(())
}

```