---
title: "clear_meta_info"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF belgesinin tüm meta bilgi değerlerini temizler."
type: docs
url: /tr/rust-cpp/core/clear_meta_info/
---

_PDF belgesinin tüm meta bilgi değerlerini temizler._

```rust
pub fn clear_meta_info(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // PDF belgesinin tüm meta bilgi değerlerini temizle
    pdf.clear_meta_info()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_clear_meta_info.pdf")?;

    Ok(())
}

```