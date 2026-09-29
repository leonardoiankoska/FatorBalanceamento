# Árvore AVL: inserção e remoção

Atividade de Estrutura de Dados sobre Árvore AVL



**Sequẽncia de inserção:  55, 26, 29, 13, 12, 11, 16, 1, 5, 29, −15, 4, 16, 8, 4, 5, 3, 1312, 100, 88** <br>
**Sequẽncia de remoção: 4, 29, 100, 5, −15, 16, 55**

## Regras Utilizadas:

* Menores á esquerda e maiores á direita
* Valores repetidos não são inseridos
* FB = Altura da esquerda - altura da direita
* Se o FB ficar entre -1 e +1, o nó está balanceado. Se chegar a +2 e -2, é feita uma rotação
* Remoção de nó com dois filhos: é usado o sucessor de menor valor



## 1. Inserções ##
**1. Inserindo 55**
<br><br>
<img width="678" height="341" alt="image" src="https://github.com/user-attachments/assets/e91fdd2c-4ef3-47e6-b44b-a63cea831089" />
<br>
Inserção Normal





**2. Inserindo 26**
<br><br>
<img width="326" height="281" alt="image" src="https://github.com/user-attachments/assets/2d3160de-5c97-4e95-85c8-d1cfe66385f8" />
<br>
Inserção Normal. O valor 26 foi inserido á esquerda do 55.


**3. Inserindo 29**<br><br>
<img width="326" height="281" alt="image" src="https://github.com/user-attachments/assets/4d496ce5-244f-4f2a-98c4-c92a17d82acd" />


<br>
Rotação LR . O valor 29 foi inserido á direita do 26, causando o desequilíbrio. Foi realizada uma rotação

**4. Inserindo 13**<br><br>
<img width="360" height="350" alt="image" src="https://github.com/user-attachments/assets/34eff4f5-e9c9-4bf4-b518-c1def3c4d0ab" />
<br>
Inserção normal. A árvore permaneceu balanceada



**5. Inserindo 12**<br><br>
<img width="360" height="350" alt="image" src="https://github.com/user-attachments/assets/5362dec1-74b5-440c-ab12-7c235b0332c1" /><br>
Rotação LL. Foi realizada uma rotação a direita para balanceá-la




**6. Inserindo 11**<br><br><img width="360" height="350" alt="image" src="https://github.com/user-attachments/assets/c8e03453-0c31-4524-ac4e-5e80fcbf7240" /><br>
Rotação LL. Houve um desequilíbrio do lado esquerdo. Foi realizada um rotação á direita


**7. Inserindo 16**<br><br> <img width="420" height="395" alt="image" src="https://github.com/user-attachments/assets/31bcb50d-a981-4040-89a6-b37006318d6f" />
<br> Inserção Normal


**8. Inserindo 1**<br><br> <img width="420" height="395" alt="image" src="https://github.com/user-attachments/assets/69c242e6-76a6-4ceb-b632-f59891fe08bf" /><br> Rotação LL.  Foi realizada uma rotação á direita


**9. Inserindo 5**<br><br> <img width="543" height="451" alt="image" src="https://github.com/user-attachments/assets/6d143d59-b3ba-4fd0-b70f-d927427c81af" /><br> Inserção normal


**10. Inserindo 29**<br><br><img width="557" height="372" alt="image" src="https://github.com/user-attachments/assets/f352894c-45a6-4c96-b940-661014cb1335" />
 <br> Valor repetido


**11. Inserindo -15**<br><br> <img width="670" height="421" alt="image" src="https://github.com/user-attachments/assets/72456891-0ecb-4f4a-859c-d657064f2078" />
<br> Inserção normal. Valor inserido no lado esquerdo


**12. Inserindo 4**<br><br><img width="670" height="421" alt="image" src="https://github.com/user-attachments/assets/d980b687-d547-4c6b-a9d9-6f760e1c115b" />

<br> Rotação LR. Foi realizada uma rotação dupla para o balanceamento

**13. Inserindo 16**<br><br><img width="670" height="421" alt="image" src="https://github.com/user-attachments/assets/6503de35-5f8a-4add-9de5-7fca2c074ba6" />

<br> Valor repetido

**14. Inserindo 8**<br><br><img width="708" height="369" alt="image" src="https://github.com/user-attachments/assets/ef85dd13-bce6-4bae-9819-ed4ae5e79567" />

<br>Inserção normal

**15. Inserindo 4**<br><br><img width="708" height="369" alt="image" src="https://github.com/user-attachments/assets/b7898a4d-9592-4a48-a90a-60b014569fb7" />

<br>Valor repetido

**16. Inserindo 5**<br><br><img width="708" height="369" alt="image" src="https://github.com/user-attachments/assets/1c81d6e3-ab85-42ea-ae04-683c714571b9" />

<br>Valor repetido

**17. Inserindo 3**<br><br><img width="708" height="473" alt="image" src="https://github.com/user-attachments/assets/36de6c99-b26c-4847-8df4-c4fae6ca2af8" />

<br>Inserção normal

**18. Inserindo 1312**<br><br><img width="708" height="473" alt="image" src="https://github.com/user-attachments/assets/8abd0ab8-78a5-4062-8a14-f378b2536402" />

<br>Inserção normal. A direita

**19. Inserindo 100**<br><br><img width="708" height="473" alt="image" src="https://github.com/user-attachments/assets/3bbb51b6-6177-4b1b-849c-15599312b2bd" />

<br> Rotação LR


**20. Inserindo 88**<br><br><img width="845" height="468" alt="image" src="https://github.com/user-attachments/assets/e1d4788a-e1f9-4693-802b-ae61125c7d3e" />

<br> Inserção normal. 

## 2. Remoções

**21. Removendo 4** <br><br><img width="705" height="445" alt="image" src="https://github.com/user-attachments/assets/190356d7-09cf-4b43-bbb8-39b646c8691b" />
<br> O 4 tem 1 filho, ele ocupa o lugar do 4. Nenhuma rotação necessária

**22. Removendo 29** <br><br><img width="705" height="445" alt="image" src="https://github.com/user-attachments/assets/7b9c5b89-d1ff-490a-8143-f13e538df15c" />
<br> O 29 tem 2 filhos, usa-se o 55 no lugar do 29

**23. Removendo 100** <br><br><img width="705" height="445" alt="image" src="https://github.com/user-attachments/assets/771efc25-b2b1-48e8-9853-2e1faf4e9363" />
<br> O 100 tem 2 filhos, usa-se o menor valor da subárvore direita,1312.

**24. Removendo 5** <br><br><img width="705" height="445" alt="image" src="https://github.com/user-attachments/assets/2f967882-b24f-4e1a-8c02-cda8ae914212" />
<br>
O 5 tem 2 filhos, usa-se o 8, que é o menor valor da subárvore direita

**25. Removendo -15** <br><br><img width="659" height="382" alt="image" src="https://github.com/user-attachments/assets/3b84802b-dddf-4b12-b270-79585bf801cb" />
<br> 

**26. Removendo 16** <br><br><img width="659" height="382" alt="image" src="https://github.com/user-attachments/assets/8642047f-2eee-4a47-83bc-c1565f198e4d" />
<br>

**27. Removendo 55** <br><br><img width="659" height="382" alt="image" src="https://github.com/user-attachments/assets/4c3df76a-b725-46a6-b08f-1a58a40e1994" />

<br> O 55 tem 2 filhos, usa-se o 88, que é o sucessor.





