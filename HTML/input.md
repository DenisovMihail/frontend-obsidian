### ⌨️ `<input>` — Поле ввода

- **Описание:** элемент для ввода данных пользователем.
    
- **Применение:** формы — текст, пароли, чекбоксы, радио и др.
    
- **Пример:**
    
    `<input type="text" name="username" placeholder="Введите имя">`
    
- **Атрибуты:**
    
    - ✅ Общие: `class`, `id`, `style`, `title`, `name`, `value`, `disabled`, `readonly`, `required`
        
    - 🔸 Специфичные:
        
        - `type` — тип ввода (`text`, `password`, `checkbox`, `radio`, `email`, `number` и др.)
            
        - `placeholder` — подсказка внутри поля
            
        - `maxlength`, `minlength` — ограничения длины
            
        - `min`, `max`, `step` — числовые ограничения
            
        - `checked` — для checkbox и radio
            
        - `autocomplete` — автозаполнение