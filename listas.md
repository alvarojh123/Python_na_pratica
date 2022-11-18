* Criar duas listas. Uma terá contúedo e a outra estará vazia 

```python
lista_01 = [1,2,3,4,5]

lista_02 = []
```

* Função q

```python
def verificar_lista(nome_da_lista):
	if nome_da_lista:
		print('lista com conteúdo')
	else:
		print('lista vazia')
```



### .append() versus .extend()


* Criamos uma lista
```python
lista = [1,2,3,4,5,6]
```

* Adicionamos um elemento (número) na lista

```python
lista.append(1)
```

```Output: [1, 2, 3, 4, 5, 6, 1] ```

* Adicionamos uma string na lista

```python
lista.append('nome')
```

```Output: [1, 2, 3, 4, 5, 6, 1, 'nome']```

* Adicionamos uma lista na lista


```python
lista_02 = ['a', 'b', 'c']

lista.append(lista_02)
```

```Output:[1, 2, 3, 4, 5, 6, 1, 'nome', ['a', 'b', 'c']]```


