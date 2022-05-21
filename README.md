### Request
```json
[
  {
    "key": "api key",
    "steam_id": "player's steam id",
    "store_id": "store id"
  }
]
```

### Response
```json
[
  {
    "steam_id": "76561198034168225",
    "balance": "1560",
    "store_id": "1",
    "items": {
      "0": {
        "name": "MP5A4",
        "identifier": "1318558775",
        "amount": "1",
        "type": "item",
        "product_id": "1",
        "images": "https://rustlabs.com/img/items180/smg.mp5.png"
      },
      "1": {
        "name": "VIP",
        "amount": "1",
        "type": "command",
        "product_id": "2",
        "images": "ссылка на картинку"
      }
    }
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
