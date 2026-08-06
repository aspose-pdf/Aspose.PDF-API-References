---
title: "page_replace_font"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Sayfadaki yazı tipini değiştirir."
type: docs
url: /tr/rust-cpp/organize/page_replace_font/
---

_Sayfadaki yazı tipini değiştirir._

```rust
pub fn page_replace_font(&self, num: i32, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **find_font_name** - the font name to search
  * **replace_font_name** - the font name to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // Sayfadaki yazı tipini değiştir
    pdf.page_replace_font(1, "Times-BoldItalic", "Helvetica-Bold")?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_page1_replace_font.pdf")?;

    Ok(())
}

```