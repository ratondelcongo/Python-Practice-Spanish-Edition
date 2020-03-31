# Dia 1

## Pregunta 1

```python
for i in range(2000,3201):
    if i%7 == 0 and i%5!=0:
        print(i,end=',')
print("\b")
```

## Pregunta 2

```python
n = int(input())
fact = 1
i = 1
while i <= n:
    fact = fact * i
    i = i + 1
print(fact)
```

## Pregunta 3

```python
n = int(input())
ans={i : i*i for i in range(1,n+1)}
print(ans)
```
