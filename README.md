### Request
```json
[
  {
    "api_key": "api key",
    "store_id": "store id",
    "steam_id": "player's steam id"
  }
]
```

api_key - Unique shop key.

store_id - The unique ID of the store.

steam_id - The Steam ID of the player.

### Response
```json
[
{
    "items": [
        {
            "id": 1,
            "name": "Товар 1",
            "contents": "Описание 1",
            "shop_id": "1",
            "identifier": "Айди товара",
            "price": "100",
            "categories": "1",
            "type": "1",
            "servers": "1",
            "quantity": "1",
            "discount": "10",
            "active": "1"
        },
        {
            "id": 2,
            "name": "Товар 2",
            "contents": "Описание2 ",
            "shop_id": "2",
            "identifier": "Айди товара",
            "price": "200",
            "categories": "1",
            "type": "1",
            "servers": "1",
            "quantity": "1",
            "discount": "10",
            "active": "0"
        }
    ]
}
]
```
1. steam_id - стим айди игрока.

2. balance - баланс игрока.

3. store_id - айди магазина.

4. items - список товаров.

5. name - Название товара.

6. identifier - уникальный ID товара.

7. amount - количество.

8. type

8.1 item - предмет.

8.2 recipe - рецепт предмета.

8.3 command - команда.

8.4 set - набор.

8.5 roulette - рулетка.

### Купить товар

```json
[
  {
    "key": "ключ",
    "steam_id": "76561198034168225",
    "store_id": "1",
    "product_id": "1"
  }
]
```
### Ответ
```json
[
  {
    "status": "true"
  }
]
```
