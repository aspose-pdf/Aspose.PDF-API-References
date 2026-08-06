---
title: "page_add_text_footer"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Sayfa altbilgi kısmına metin ekler."
type: docs
url: /tr/rust-cpp/organize/page_add_text_footer/
---

_Sayfa altbilgi kısmına metin ekler._

```rust
pub fn page_add_text_footer(&self, num: i32, footer: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **footer** - the pages footer

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // Sayfa altbilgisine metin ekle
    pdf.page_add_text_footer(1, "FOOTER")?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_page1_add_text_footer.pdf")?;

    Ok(())
}

```