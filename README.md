# Django Polls

Resmi Django (Tutorial 1-8) takip edilerek geliştirilmiş anket uygulaması ve bağımsız Python paketi (`django-polls`).

## Özellikler
- Soru listeleme, oylama ve anlık sonuç görüntüleme
- Özelleştirilmiş Django Admin paneli
- Birim (unit) testleri
- `pyproject.toml` ile bağımsız, yeniden kullanılabilir kütüphane yapısı

## Kurulum ve Çalıştırma

```bash
# 1. Sanal ortamı açın ve paketi kurun
python -m pip install -e django-polls

# 2. Veritabanını hazırlayın
cd djangotutorial
python manage.py migrate

# 3. Sunucuyu başlatın
python manage.py runserver
