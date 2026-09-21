# Gerador-da-Sequencia-de-Fibonacci
Gerador da sequencia de Fibonacci pela quantidade de termos inseridos pelo usuario

O controle de fluxo é feito por um laço while que utiliza um contador i. Esse laço se repete até que o contador alcance o valor n digitado pelo usuário. Isso garante que o programa calcule e imprima exatamente a quantidade de termos solicitada, sem gerar números a mais. Para que a sequência avance, o algoritmo utiliza a variável soma para calcular o próximo número a partir da adição de n1 e n2. Após este cálculo, os valores base são deslocados: n1 assume o valor de n2, e n2 assume o valor da soma. Esta abordagem de substituição garante que as variáveis não fiquem estáticas e que o ciclo utilize sempre os dois termos mais recentes para gerar o próximo número.

Para executar este programa na sua máquina, você deve compilá-lo no terminal usando o comando:
gcc fibonacci.c -o fibonacci
Por fim, execute-o com o comando:
fibonacci.exe (no Windows) ou ./fibonacci (no Linux/Mac).
