 ConversorDeMoedas
Este programa Java permite aos usuários converter valores entre diferentes moedas, utilizando a API ExchangeRate-API para obter as taxas de câmbio em tempo real.

Funcionalidade
Solicita ao usuário um valor e as moedas de origem e destino.
Realiza a conversão utilizando a API ExchangeRate-API.
Salva o resultado em um arquivo JSON.
Recursos Utilizados
JOptionPane: Para entrada do usuário e exibição de mensagens.
HttpClient: Para fazer a requisição HTTP à API ExchangeRate-API.
Gson: Para processar a resposta JSON.
Como Usar
Execute o programa.
Insira seu nome e escolha a conversão desejada no menu.
Insira os valores solicitados para realizar a conversão.
🔍 ConversorDeMoedas
Classe Principal: Main
Esta classe lida com a interface gráfica e a lógica do menu de conversão.

Descrição
JOptionPane: Utilizado para criar a interface gráfica que solicita ao usuário que insira seu nome e escolha as opções do menu.
TextMenu: Fornece o texto do menu baseado no nome do usuário.
Conversor: Realiza a conversão das moedas e gera o arquivo JSON com o resultado.
