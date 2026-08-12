---
title: "save_tex"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Daha önce açılmış PDF-dokümanını TeX-dokümanı olarak dönüştürür ve kaydeder."
type: docs
url: /tr/rust-cpp/convert/save_tex/
---

_Daha önce açılmış PDF-dokümanını TeX-dokümanı olarak dönüştürür ve kaydeder._

```rust
pub fn save_tex(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // Daha önce açılmış PDF-dokümanını TeX-dokümanı olarak dönüştür ve kaydet
    pdf.save_tex("sample.tex")?;

    Ok(())
}

```