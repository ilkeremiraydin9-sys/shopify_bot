# Shopify Bot 🤖

Bu bot, Shopify mağazanızı yönetmek için basit bir API sağlar.

## Özellikler
- Sağlık kontrolü (`/health`)
- Shopify API bağlantısı için temel yapı
- Ortam değişkenleri desteği (.env dosyası)

## Kurulum
```bash
# Reponuzu klonlayın
git clone https://github.com/<kendi-kullanıcı-adın>/shopify_bot.git
cd shopify_bot

# Sanal ortam oluşturun
python -m venv .venv
source .venv/bin/activate

# Bağımlılıkları yükleyin
pip install -r requirements.txt

# Örnek ortam dosyasını kopyalayın
cp .env.example .env

# Çalıştırın
python app.py
