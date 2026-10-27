# Atividade-Avaliativa-Aplica-o-do-Algoritmo-Bubble-Sort
Sistema de Ordenação de Preços de Supermercado
1. Identificação do projeto

Disciplina: Algoritmos e pensamento computacional
Professora: Profa. Karla R. Sartin
Linguagem de programação: C
Algoritmo utilizado: Bubble Sort

Integrante
João Pedro Guimarães de Lima Cruvinel

2. Contextualização

Nos supermercados, comparar preços é uma atividade importante para consumidores e responsáveis pelas compras. Quando existem diversos produtos, organizar seus preços facilita a identificação das opções mais baratas e mais caras.

Este projeto apresenta uma aplicação desenvolvida em linguagem C que organiza os preços de dez produtos utilizando o algoritmo Bubble Sort.

3. Objetivo

Desenvolver uma aplicação que utilize arrays, estruturas de repetição, estruturas condicionais e o algoritmo Bubble Sort para ordenar preços de produtos em ordem crescente.

O programa também apresenta os preços antes e depois da ordenação e identifica o menor e o maior valor.

4. Funcionamento do Bubble Sort

O Bubble Sort compara elementos adjacentes de um array. Quando dois elementos estão fora da ordem desejada, seus valores são trocados.

Neste projeto, a ordenação é crescente. Portanto, quando o preço atual é maior que o próximo preço, ocorre uma troca.

O procedimento é repetido até que todos os preços estejam ordenados.

O algoritmo utiliza:

Um array com dez preços.
Laços for para percorrer os elementos.
Uma estrutura if para comparar os preços.
Uma variável temporária para realizar as trocas.

A complexidade de tempo do Bubble Sort tradicional é O(n²) no pior caso, sendo adequado para demonstrar os fundamentos dos algoritmos de ordenação.

5. Tecnologias e ferramentas
Linguagem C.
Compilador GCC.
Git para controle de versão.
GitHub para hospedagem do código-fonte.
Visual Studio Code, Code::Blocks ou outro editor compatível.
6. Como compilar e executar

É necessário ter um compilador C, como o GCC, instalado.

Compilação

No terminal, dentro da pasta do projeto, execute:

bash
gcc -Wall -Wextra -std=c11 main.c -o supermercado

Execução no Linux ou macOS
bash
./supermercado

Execução no Windows
bash
supermercado.exe

7. Exemplo de entrada e saída

O programa utiliza dez preços definidos inicialmente no código, dispensando a digitação de dados pelo usuário.

Preços originais
text
12.50, 5.99, 18.75, 3.49, 9.90,
25.00, 7.25, 15.30, 2.99, 11.40

Preços ordenados
text
2.99, 3.49, 5.99, 7.25, 9.90,
11.40, 12.50, 15.30, 18.75, 25.00


O menor preço é R$ 2,99 e o maior é R$ 25,00.

Substitua SEU-USUARIO pelo nome de usuário real do GitHub e utilize a URL do repositório criado.

8. Considerações finais

O desenvolvimento deste projeto permite aplicar conceitos fundamentais da linguagem C, incluindo arrays, laços de repetição, condicionais e manipulação de variáveis.

A implementação do Bubble Sort demonstra como comparações e trocas entre elementos adjacentes permitem organizar dados. A aplicação também evidencia a importância do controle de versão e da documentação para a organização de projetos de software.
