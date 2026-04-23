# Boot Telegram Payment Gateway

Telegram bot dengan integrasi payment gateway untuk top up dan transaksi pembayaran.

## Fitur Utama
- 🤖 Bot Telegram interaktif
- 💳 Integrasi Payment Gateway
- 💰 Sistem Top Up Balance
- 👤 Manajemen User
- 📊 Database Management
- 📝 Logging dan Monitoring

## Persyaratan
- Python 3.8+
- Token Bot Telegram
- Credentials Payment Gateway

## Instalasi

1. Clone repository:
```bash
git clone https://github.com/Sihabhanapi/boot-telegram-payment-gateway.git
cd boot-telegram-payment-gateway
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Setup environment variables:
```bash
cp .env.example .env
# Edit .env dengan credentials Anda
```

4. Jalankan bot:
```bash
python bot.py
```

## Struktur Proyek

```
boot-telegram-payment-gateway/
├── bot.py                 # Main bot application
├── config.py             # Configuration settings
├── payment_handler.py    # Payment gateway integration
├── database.py           # Database operations
├── requirements.txt      # Python dependencies
├── .env.example          # Environment variables template
├── .gitignore           # Git ignore rules
└── README.md            # Documentation
```

## Konfigurasi

Edit file `.env` dengan:
- `TELEGRAM_BOT_TOKEN` - Token dari BotFather
- `PAYMENT_GATEWAY_KEY` - API key payment gateway
- `DATABASE_URL` - Database connection string

## Penggunaan

Bot akan merespons perintah berikut:
- `/start` - Mulai interaksi dengan bot
- `/balance` - Cek saldo akun
- `/topup` - Melakukan top up
- `/history` - Riwayat transaksi

## Contributing

Silakan submit issues dan pull requests untuk kontribusi.

## License

MIT License