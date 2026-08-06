---
title: "add_page_num"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-document'e sayfa numarası ekler."
type: docs
url: /tr/rust-cpp/organize/add_page_num/
---

_PDF-document'e sayfa numarası ekler._

```rust
pub fn add_page_num(&self) -> Result<(), PdfError>
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

    // PDF-dokümanına sayfa numarası ekle
    pdf.add_page_num()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_add_page_num.pdf")?;

    Ok(())
}

```