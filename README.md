# My Language Trainer

A small terminal quiz for English → Turkish vocabulary (113 words). It asks a random word, you type its Turkish meaning, and it keeps score. One of the first programs I wrote while learning Python, between July and November 2023, kept here as it was.

## Run

Requires Python 3; no extra packages.

```bash
python3 main.py
```

Type `exit`, `quit` or `stop` to finish and see your score.

## Notes

- The code is kept exactly as written back then; only line endings were normalized.
- A correct answer gives 1 point and removes the word; a wrong answer costs 0.5 points and the word stays in the pool.
- Meanings starting with a capital "İ" (İşemek, İşaret, İstekli) cannot be answered correctly, because Python's `lower()` does not follow Turkish casing rules.
- Originally published in July 2023 (version 1.01.001, first upload) and updated in August 2023 (version 1.01.002, word list update).

## License

[MIT](LICENSE)

---

## Dil Çalıştırıcım (Türkçe)

İngilizce → Türkçe kelime çalışması için küçük bir terminal sınavı (113 kelime). Rastgele bir kelime sorar, sen Türkçe anlamını yazarsın, puanını tutar. Python öğrenirken, Temmuz ile Kasım 2023 arasında yazdığım ilk programlardan biri; hatıra olarak olduğu gibi saklanıyor.

### Çalıştırma

Python 3 yeterli; ek paket gerekmez.

```bash
python3 main.py
```

Bitirip puanını görmek için `exit`, `quit` ya da `stop` yaz.

### Notlar

- Kod o zaman yazıldığı gibi duruyor; yalnızca satır sonları düzenlendi.
- Doğru cevap 1 puan kazandırır ve kelime listeden çıkar; yanlış cevap 0,5 puan götürür ve kelime listede kalır.
- Büyük "İ" ile başlayan anlamlar (İşemek, İşaret, İstekli) doğru cevaplanamaz, çünkü Python'un `lower()` işlevi Türkçe büyük-küçük harf kurallarına uymaz.
- İlk olarak Temmuz 2023'te yayımlandı (1.01.001 sürümü, ilk yükleme), Ağustos 2023'te güncellendi (1.01.002 sürümü, kelime listesi güncellemesi).

### Lisans

[MIT](LICENSE)
