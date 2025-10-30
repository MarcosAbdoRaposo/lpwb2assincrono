# lpwb2assincrono
Exercício de Chamada Assincrona

Autor: Marcos Abdo Raposo

Promise, fetch e async/await são ferramentas essenciais para lidar com operações assíncronas em JavaScript, mas servem a propósitos diferentes e representam a evolução na forma de lidar com a assincronicidade.


|Característica|	Promise|	Fetch|	Async/Await|


|O que é | 

Promisse: Um objeto que representa a conclusão ou falha eventual de uma operação assíncrona. 

Fetch: Uma API para fazer requisições HTTP.

Async/Await: Melhoria sintática sobre as Promises, tornando o código assíncrono mais limpo e legível.


Como Funciona:

Promisse: Você encadeia métodos .then() para tratar o sucesso e .catch() para tratar o erro.

Fetch: A função fetch() retorna uma Promise, que você pode usar com .then() e .catch() para tratar a resposta.

Async/Await : Usa as palavras-chave async (em uma função) e await (para pausar a execução até a Promise ser resolvida).


Legibilidade:

Promisse::	Pode levar a um encadeamento de código complexo ("callback hell") em cenários mais elaborados.	
    
    
Fetch: A sintaxe .then() em cadeia pode ser menos legível que async/await para operações sequenciais.	
    
Async/Await: O código se parece e se comporta como código síncrono, sendo mais fácil de ler e entender.





