[nãoclickaqui](https://chatgpt.com/)

# a
Listas e sequências são indexadas por inteiros, ao passo que dicionários podem ser indexados por 'strings'.

# b
Qual comando do Python 3 que realiza para cada lista uma atribuição do elemento corrente à variável definida no comando e executa o bloco de código associado a essa variável disponível?
> for

```python
a, b = 0, 1
while a<= 14:
    if (a % 2) == 1:
        print(a)
    a, b = b, a+b
```
> 1 1 3 5 13

```python
def ABC(L, n):
      while True:
             if len(L) >= n:
                 return L
           else:
                 L.append(len(L) ** 2)
print(ABC([20],10))
```
> [20, 1, 4, 9, 16, 25, 36, 49, 64, 81]

```python
x = 7*3**2 % 4
print(x)
```
> 3

```python
L=[1]
while len(L) < 6:
    L.append(L[-1]*len(L))
print(L)
```
> [1, 1, 2, 6, 24, 120]

```python
x = [1,2,3,4,5]
print(x[::-1])
```
> [5, 4, 3, 2, 1]

```python
>>> matriz = [[1,2,3], [4,5,6],[7,8,9]]
>>> matriz[2][1]
```
> 8

```python
x = [1,2,3,4,5]
print(x[-1])
```
> 5

```python
def F(a, b, c):
      for k in range(a,b):
           print(k ** c)
# 16, 9, 4, 1, 0, 1
```
> 

```python
def F(a, b, c):
    for k in range(a, b):
        print(k ** c)
F(-4,2,2)
```
> -4,2,2

```python
L=["A","E","I","O","U"]
for k in range(0,len(L)):
    print (L[4-k])
```
> U O I E A

```python
names = ["John", "Sophie", "Junior"]
for x in names:
    print(x)
```
