# Discord-bot-modular

/project
│
├── bot.py          # File utama untuk menjalankan bot
├── config.py       # Token bot dan konfigurasi
│
├── commands/       # Folder untuk modular commands
│   ├── __init__.py # Menginisialisasi commands sebagai package
│   ├── admin_commands/
│   │   ├── __init__.py
│   │   ├── kick.py
│   │   ├── ban.py
│   │   ├── clear.py
│   │   ├── server_info.py
│   │   ├── setup_ticket.py
│   │   ├── warn.py
│   │   ├── feedback.py
│   │   ├── embedsend.py
│   │   ├── lock.py
│   │   ├── unlock.py
│   │   ├── giveaway.py
└── requirements.txt # Library yang dibutuhkan
