---
title: "page_replace_text"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Sayfadaki metni değiştirir."
type: docs
url: /tr/rust-cpp/organize/page_replace_text/
---

_Sayfadaki metni değiştirir._

```rust
pub fn page_replace_text(&self, num: i32, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **find_text** - the text fragment to search
  * **replace_text** - the text fragment to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // Sayfadaki metni değiştir
    pdf.page_replace_text(1, "PDF", "TXT")?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_page1_replace_text.pdf")?;

    Ok(())
}

```