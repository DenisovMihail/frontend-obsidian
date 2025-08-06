### 📬 `<form>` — Форма

- **Описание:** контейнер для сбора и отправки данных пользователя на сервер.
    
- **Применение:** регистрация, вход, поисковые строки, анкеты и опросы.
    
- **Пример:**
    
    `<form action="/submit" method="post">     <input type="text" name="username">     <button type="submit">Отправить</button> </form>`
    
- **Атрибуты:**
    
    - ✅ Общие: `class`, `id`, `style`, `title`
        
    - 🔸 Специфичные:
        
        - `action` — URL для отправки данных
            
        - `method` — метод (`get`, `post`)
            
        - `enctype` — тип кодировки (`multipart/form-data`, и др.)
            
        - `autocomplete` — автозаполнение (`on` / `off`)
            
        - `target` — куда отправляется результат (`_self`, `_blank`)
            
        - `novalidate` — отключить валидацию HTML5