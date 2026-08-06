---
title: "set_meta_info"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF belgesinin meta bilgi değerini ayarlar."
type: docs
url: /tr/rust-cpp/core/set_meta_info/
---

_PDF belgesinin meta bilgi değerini ayarlar._

```rust
pub fn set_meta_info(&self, key: &str, value: &str) -> Result<(), PdfError>
```

**Arguments**
  * **key** - the key whose value to set
  * **value** - the value to be set

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // PDF belgesinin meta bilgi değerini ayarla
    pdf.set_meta_info("Author", "Aspose")?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_set_meta_info.pdf")?;

    Ok(())
}

```