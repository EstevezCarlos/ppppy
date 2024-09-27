# [PPPPY](../)

## Podstawy

### Podstawowe funkcje wbudowane

```python
print			# wyświetla argumenty (domyślnie w konsoli)
input			# zwraca wartość podaną przez użytkownika w konsoli
################################################################################
any				# zwaraca prawdę jeżeli choć jeden z argumentów jest prawdziwy
all				# zwraca prawdę jeżeli wszystkie argumenty są prawdziwe
################################################################################
len				# zwraca długość (ilość elementów) kolekcji
next			# zwraca następny element iteratora/generatora
sorted			# zwraca listę posortowanych elementów
reversed		# zwraca odwróconą listę
################################################################################
abs				# zwraca wartość bezwzględną liczby
```



### Podstawowe typy

```python
#typy proste
int		# integer - liczba całkowita
float	# float - liczba rzeczywista/zmiennoprzecinkowa
bool	# boolean - wartość logiczna 1 lub 0 (True lub False)
str		# string - sekwencja znaków, czyli tekst

#kolekcje
tuple	# () - krotka - sekwencja indeksowana, niemutowalna
list	# [] - lista - sekwencja indeksowana, mutowalna
set		# {} - zbiór - kolekcja nieuporządkowana, mutowalna, zawierająca unikalne, niemutowalne elementy
dict	# {} - słownik - kolekcja wartości przypisanych unikalnym, niemutowalnym kluczom, mutowalna
range	# ciąg - sekwencja, uporządkowana, niemutowalna
```

### Opreratory

```python
=	# operator przypisania

# Arytmetyczne
3 + 3		# dodawanie
3 - 3		# odejmowanie
3 * 3		# mnożenie
3 / 3		# dzielenie z wynikiem float
3 // 3		# dzielenie z wynikiem zaokrąglonym w dół
3 ** 3		# potęgowanie

# operatory porównania
a == b		# True jeżeli a jest równe b
a != b		# True jeżeli a nie jest równe b
>			# True jeżeli a jest większe niż b
>=			# True jeżeli a jest większe niż lub równe b
<			# True jeżeli a jest mniejsze niż b
<=			# True jeżeli a jest mniejsze niż lub równe b
a in b		# True jeżeli a jest elementem kolekcji b
a not in b	# True jeżeli a nie jest elementem kolekcji b
a is b		# True jeżeli zmienne a oraz b wskazują na ten sam obiekt
a is not b	# True jeżeli zmienne a oraz b nie wskazują na ten sam obiekt

#operatory logiczne
a and b		# True jeżeli a i b są równe True
a or b		# True jeżeli a lub b lub oba są równe True
not a		# True jeżeli a jest równe False

#operatory bitowe
|	# bitowy or
&	# bitowy and
^	# bitowy xor

#operatory sekwencji
'a' + 'b'	# konkatenacja
'a' * 3		# powielenie

# operatory zbiorów
|	# union
&	# intersection
-	# difference
^	# symmetric difference
>=	# issuperset
<=	# issubset

# skrótowe operatory przypisania
a += b	# powiększa wartość zmiennej a o b
a -= b	# pomniejsza wartość zmiennej a o b
a *= b	# b-krotnie powiększa wartość zmiennej a
# itd. dla każdego arytmetycznego, bitowego, sekwencji i zbiorów
```

