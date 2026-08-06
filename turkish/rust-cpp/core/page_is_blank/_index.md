---
title: "page_is_blank"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dökümanındaki sayfanın boş olup olmadığını döndür."
type: docs
url: /tr/rust-cpp/core/page_is_blank/
---

_PDF belgesinde sayfa boştur._

```rust
pub fn page_is_blank(&self, num: i32) -> Result<bool, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosyadan bir PDF-document aç
    let pdf = Document::open("sample.pdf")?;

    // Sayfa numarasını belirtin (1 tabanlı indeks)
    let page_number = 1;

    // PDF belgesinde sayfa boştur
    let is_blank = pdf.page_is_blank(page_number)?;

    // Belirtilen sayfa boşsa yazdır
    println!("Is page {} blank? {}", page_number, is_blank);

    Ok(())
}

```