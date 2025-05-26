# 📘 Описание полей `orders_report.xlsx`

| Поле            | Тип        | Описание                                           |
|------------------|------------|----------------------------------------------------|
| `order_id`       | int        | Уникальный ID заказа                               |
| `client_id`      | int        | Уникальный ID клиента                              |
| `product_name`   | str        | Название товара (Product A, B, C)                  |
| `channel`        | str        | Канал продаж (online, retail, partner)             |
| `quantity`       | int        | Количество единиц в заказе                         |
| `price_per_unit` | float      | Цена за единицу                                    |
| `order_date`     | datetime   | Дата оформления заказа                             |
| `total`          | float      | Общая сумма заказа (quantity * price_per_unit)     |
