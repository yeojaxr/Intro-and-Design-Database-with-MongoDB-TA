## Nomor 1
Relasinya adalah one-to-one
```
{
    "_id": ObjectId("1"),
    "full_name": "John Doe",
    "email": "john@doe.com",
    "phone_number": "0857665342"
}
```

## Nomor 2
Relasinya adalah one-to-many
```
{
    "_id": ObjectId("1"),
    "full_name": "John Doe",
    "email": "john@doe.com",
    "phone_number": "0857665342",
    "address":[
        "jalan melati",
        "jalan mawar"
    ]
}
```

## Nomor 3
Relasinya adalah one-to-many
```
{
    "_id": ObjectId("1"),
    "product_name" : "kaos polos",
    "brand_name" : "Skillshirt",
    "variants": [
        {
            "name": "kaos polos hitam",
            "color": "hitam",
            "quantity": 12,
            "price": 99000
        },
        {
            "name": "kaos polos navy",
            "color": "navy",
            "quantity": 10,
            "price": 99000
        }
    ]
}
```

## Nomor 4
Relasinya many-to-many
```
[{
    "name": "CGF",
    "location": "pondok indah mall",
    "films": [
        {
            "name": "venom 2"
        },
        {
            "name": "spiderman no way home"
        }
    ]
}
{
    "name": "Cinema31",
    "location": "mall kelapa gading",
    "films": [
        {
            "name": "venom 2"
        },
        {
            "name": "spiderman no way home"
        }
    ]
}]
```