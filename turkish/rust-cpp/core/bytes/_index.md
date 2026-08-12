---
title: "bayt"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dökümanının içeriğini bayt vektörü olarak döndürür."
type: docs
url: /tr/rust-cpp/core/bytes/
---

_PDF-dökümanının içeriğini bayt vektörü olarak döndürür._

```rust
pub fn bytes(&self) -> Result<Vec<u8>, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Vec\<u8\>)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Yeni bir PDF-document oluştur
    let pdf = Document::new()?;

    // PDF-dökümanının içeriğini bayt vektörü olarak döndür
    let data = pdf.bytes()?;

    // Bayt vektörünün uzunluğunu yazdır
    println!("Length: {}", data.len());

    Ok(())
}

```