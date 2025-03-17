# 🗂️ Atividade usando branch

Esta aplicação se encontra incompleta e com falhas, necessário criar sua **branch** e enviar as devidas correções permitindo ser executada.

## 🎰 Atividade Mega-Sena

**🎲 1ª FASE:** Criar um programa que gere de forma aleatória as 6 dezenas. 
Exemplo: 51-31-20-38-34-42

**🎲 2ª FASE:** Criar um bolão, no qual, permite o usuário informar a quantidade de jogos de 6 dezenas que deseja fazer 

**🎲 3ª FASE:** Criar o jogo no qual permite o usuário informar a quantidade de jogos e quantidade de dezenas.

```
Exemplo:
	2 jogos de 7 dezenas 	20-30-54-22-24-52-60
				20-22-35-15-40-22-10

	10 jogos de 6 dezenas	20-30-54-22-24-52
				20-22-35-15-40-22
				...
```

**🎲 4ª FASE:** Solicitar que o usuário informe novamente o número de dezenas caso seja informado por ele o valor menor que 6 ou maior que 15

**🎲 5ª FASE:** Salvar o jogo/bolão em um arquivo .TXT
```
	using System.IO;

	using (StreamWriter escrever = new StreamWriter("jogos-mega-sena.txt"))
	{
    		Console.WriteLine("Teste");  // Imprime na tela
    		escrever.WriteLine("Teste"); // Salva no arquivo
	}
```

**🎲 6ª FASE:** Solicitar que o usuário informe o valor do prêmio

**🎲 7ª FASE:** Determinar que 75% do prêmio será para quem acertar as 6 dezenas, 15% para quem acertar 5 dezenas e 10% para quem acertar 4 dezenas.

<!--**8ª FASE:** Permitir que o sistema realize o sorteio de 6 dezenas aleatórias e dizer se deu ganhador: Mega-Sena, Quina e Quadra.-->
