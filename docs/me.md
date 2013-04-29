# Пользователь

### `GET /me` — текущий авторизованный пользователь

```json
{
    "first_name": "Имя",
    "last_name": "Фамилия",
    "is_admin": false,
    "is_anonymous": false,
    "is_applicant": true,
    "is_employer": false,
    "mid_name": "Отчество",
    "email": "contact@example.com"
}
```

В случае отсутствия или передачи неправильной авторизации сервер ответит `403 Forbidden`.
