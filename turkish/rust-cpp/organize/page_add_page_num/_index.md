---
title: "page_add_page_num"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Sayfaya sayfa numarası ekler."
type: docs
url: /tr/rust-cpp/organize/page_add_page_num/
---

_Sayfaya sayfa numarası ekler._

```rust
pub fn page_add_page_num(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // Sayfaya sayfa numarası ekle
    pdf.page_add_page_num(1)?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_page1_add_page_num.pdf")?;

    Ok(())
}

```