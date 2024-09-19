
____

```SQL
SELECT model
FROM `products` 
WHERE maker = 'B'
```

____

```SQL
SELECT model
FROM `products` 
WHERE NOT (maker = 'B')
```

____

```SQL
SELECT model, maker
FROM `products` 
WHERE NOT (maker = 'B');
```

____

```SQL
SELECT *
FROM `pcs` 
WHERE speed >= 3.00;
```

____

