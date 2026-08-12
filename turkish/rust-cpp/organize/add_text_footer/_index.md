---
title: "add_text_footer"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-document'in Altbilgi kısmına metin ekler."
type: docs
url: /tr/rust-cpp/organize/add_text_footer/
---

_PDF-document'in Altbilgi kısmına metin ekler._

```rust
pub fn add_text_footer(&self, footer: &str) -> Result<(), PdfError>
```

**Arguments**
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

    // PDF-dokümanının altbilgisine metin ekle
    pdf.add_text_footer("FOOTER")?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_add_text_footer.pdf")?;

    Ok(())
}

```