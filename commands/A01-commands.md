
____

```bash
SELECT model
FROM `products` 
WHERE maker = 'B'
```

____

```bash
SELECT model
FROM `products` 
WHERE NOT (maker = 'B')
```

____

```bash
SELECT model, maker
FROM `products` 
WHERE NOT (maker = 'B');
```
