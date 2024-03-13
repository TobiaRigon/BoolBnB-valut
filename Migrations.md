![[BoolBnB_db_ER.drawio-1.pdf]]
### Apartments

- `title`: stringa (`string`)
- `description`: testo (`text`)
- `max_guests`: intero (`integer`)
- `rooms`: intero (`integer`)
- `main_img`: stringa (`string`)
- `address`: stringa (`string`)
- `longitude`: decimale (`decimal`)
- `latitude`: decimale (`decimal`)
- `price`: decimale (`decimal`)
- `beds`: intero (`integer`)
- `baths`: intero (`integer`)
### Messages

- `message`: testo (`text`)
- `sender_text`: stringa (`string`)
- `data`: data e ora (`timestamp`)
- `sender_mail`: stringa (`string`)
- `sender_name`: stringa (`string`)
- `sender_surname`: stringa (`string`)
### User_data

- `surname`: stringa (`string`)
- `data`: data (`date`)
- `name`: stringa (`string`)