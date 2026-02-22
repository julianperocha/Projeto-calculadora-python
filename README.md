# **Calculadora Python - Projeto EBAC**



### Projeto desenvolvido durante o curso de Cientista de Dados da EBAC





###### Descrição



Este projeto é uma calculadora simples em Python executada no terminal. Ela permite realizar operações básicas entre dois números:



* Soma
* Subtração
* Multiplicação
* Divisão (com verificação de divisão por zero)



O programa roda em loop e pergunta ao usuário se deseja fazer outra operação ao final de cada cálculo.



###### Funcionalidades



* Entrada de dois números (valores decimais permitidos).
* Menu para escolher a operação.
* Exibição do cálculo e do resultado.
* Tratamento de:
* Operação inválida (opção fora do menu)
* Divisão por zero
* Possibilidade de repetir operações até o usuário encerrar.





###### Requisitos



* Python 3.x



###### Como executar



1. Salve o código em um arquivo, por exemplo: calculadora.ipynb
2. Execute no terminal:



calculadora.ipynb





###### Como usar



1. Digite o primeiro número.
2. Digite o segundo número.
3. Escolha a operação digitando uma das opções:



&nbsp;	- 1 para somar

&nbsp;	- 2 para subtrair

&nbsp;	- 3 para multiplicar

&nbsp;	- 4 para dividir



4\. Veja o resultado exibido.

5\. Responda se deseja continuar:



&nbsp;	- s para fazer outra operação

&nbsp;	- n para encerrar





###### Exemplo de execução





CALCULADORA



Digite o primeiro número: 10

Digite o segundo número: 2



1 - Somar

2 - Subtrair

3 - Multiplicar

4 - Dividir



Escolha a operação: 4



Resultado: 10.0 ÷ 2.0 = 5.0



Deseja fazer outra operação? (s/n): n



Calculadora encerrada!



###### Observações



* O programa converte os valores digitados para float, então aceita números inteiros e decimais.
* A continuação do programa depende da entrada s (maiúscula ou minúscula), pois é usado continuar.lower() == "s".





###### Estrutura do código (resumo)



* Um laço while controla a repetição.
* input() é usado para coletar números e a opção da operação.
* if/elif/else define qual operação será executada.
* Para divisão, há uma verificação para evitar divisão por zero.





###### Licença



Projeto livre para uso e modificação para fins de estudo.



