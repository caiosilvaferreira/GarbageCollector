# Garbage collector, Desalocação por escopo

![Untitled](Garbage%20collector,%20Desalocac%CC%A7a%CC%83o%20por%20escopo%2033215143d9a24b9cb4d2a93b82d22dde/Untitled.png)

chama coletor de lixo, ele excluir aquilo que não esta sendo usado. ele faz essa detecção automaticamente

![Untitled](Garbage%20collector,%20Desalocac%CC%A7a%CC%83o%20por%20escopo%2033215143d9a24b9cb4d2a93b82d22dde/Untitled%201.png)

![Untitled](Garbage%20collector,%20Desalocac%CC%A7a%CC%83o%20por%20escopo%2033215143d9a24b9cb4d2a93b82d22dde/Untitled%202.png)

nesse ex de cima ele vai excluir o primeiro bloco que agora ninguem aponta nenhum resultado para ele.

# Desalocação por escopo

![Untitled](Garbage%20collector,%20Desalocac%CC%A7a%CC%83o%20por%20escopo%2033215143d9a24b9cb4d2a93b82d22dde/Untitled%203.png)

nesse ex de cima ele vai excluir o que esta dentro do if, ele deleta o valor y=20 porque ele faz parte de um escopo local, não faz parte do escopo geral que é o codigo principal

![Untitled](Garbage%20collector,%20Desalocac%CC%A7a%CC%83o%20por%20escopo%2033215143d9a24b9cb4d2a93b82d22dde/Untitled%204.png)
