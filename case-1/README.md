Кейс 1: Nginx + HTTPS + Безопасность
- Два сайта на одном сервере (виртуальные хосты)
- Редирект HTTP → HTTPS
- SSL-сертификат
- Заголовки безопасности (X-Frame-Options, X-Content-Type-Options, X-XSS-Protection)
- Скрытие версии Nginx (server_tokens off)
- Fail2ban для защиты от брутфорса
- Файрвол UFW (порты 22, 80, 443)
- Проверка конфига (nginx -t)
