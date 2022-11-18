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

```python

lista = [1,2,3,4,5,6]

lista.append(1)
```

```Output: [1, 2, 3, 4, 5, 6, 1] ```
