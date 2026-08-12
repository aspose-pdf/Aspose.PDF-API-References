---
title: "save_n_up"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Daha önce açılmış PDF-dokümanını N-Up PDF-dokümanı olarak dönüştürür ve kaydeder."
type: docs
url: /tr/rust-cpp/convert/save_n_up/
---

_Daha önce açılmış PDF-dokümanını N-Up PDF-dokümanı olarak dönüştürür ve kaydeder._

```rust
pub fn save_n_up(&self, filename: &str, columns: i32, rows: i32) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file
  * **columns** - the number of columns
  * **rows** - the number of rows

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // Daha önce açılmış PDF-dokümanını N-Up PDF-dokümanı olarak dönüştür ve kaydet
    pdf.save_n_up("sample_n_up.pdf", 2, 2)?;

    Ok(())
}
```