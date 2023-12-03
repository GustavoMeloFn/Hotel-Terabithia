# Sistema de Gerenciamento de Hotel

Este projeto é um sistema de gerenciamento de hotel modular, desenvolvido com partes independentes. O objetivo é criar uma plataforma para uso dos funcionários do hotel, não dos hóspedes.

### Requisitos Iniciais:
- Perguntar o nome do hotel e exibir "O nome do hotel é {Hotel}".
- Solicitar nome de usuário e senha (2678) durante o acesso.
- Utilizar a estrutura de escolha/caso (switch/case) na função "inicio".
- Saudar o usuário ao acessar o sistema: "Bem-vindo ao Hotel {Hotel}, {Nome}. É um imenso prazer ter você por aqui!".
- Substituir as expressões {Hotel} e {Nome} pelo nome do hotel e usuário, respectivamente.
- Exibir a mensagem "Muito obrigado e até logo, {Nome}." ao sair do sistema.

### Módulos Principais:

#### 1) Quantos quartos são?
Este módulo permite a reserva de quartos no hotel.

- Recebe o valor da diária e a quantidade de dias de hospedagem.
- Valida as informações, impedindo valores negativos e dias superiores a 30.
- Solicita o nome do hóspede e confirma a reserva.

#### 2) Como soletra?
Este módulo trata do cadastro de hóspedes, considerando gratuidades e meias hospedagens.

- Pergunta o valor padrão da diária e cadastra hóspedes informando nome e idade.
- Calcula gratuidades e meias hospedagens, exibindo as informações no final.

#### 3) Com "S" ou com "Z"?
Este módulo permite o cadastro, pesquisa e listagem de hóspedes.

- Oferece um menu com opções: cadastrar, pesquisar, listar e sair.
- Possibilita o cadastro de até 15 hóspedes, com busca e listagem.

#### 4) Festa ou trabalho?
Neste módulo, o hotel atende a eventos, calculando o custo dos garçons.

- Recebe o número de garçons e total de horas do evento.
- Calcula o custo total e permite a confirmação da reserva.

#### 5) Hora de comer
Este módulo trata do Buffet do hotel para eventos.

- Recebe a quantidade de convidados, calcula café, água, salgados e custo total.
- Verifica se a capacidade máxima do salão é respeitada.
- Permite a confirmação da reserva.

#### 6) Auditório para quantos?
O hotel seleciona o auditório adequado com base no número de convidados.

- Avalia a capacidade dos auditórios Laranja e Colorado.
- Informa se é necessário incluir cadeiras adicionais.
- Permite a confirmação da reserva.

#### 7) Que horas você pode?
Para eventos, o hotel oferece reserva do restaurante em horários específicos.

- Recebe o dia da semana e a hora do evento.
- Informa se o restaurante está disponível e permite a reserva.

#### 8) Álcool ou gasolina?
O hotel decide onde abastecer o carro, considerando preços de álcool e gasolina.

- Recebe os valores nos postos Wayne Oil e Stark Petrol.
- Calcula e informa onde é mais vantajoso abastecer.

#### 9) Ar puro, finalmente.
Este módulo lida com a manutenção de ar-condicionados, buscando o melhor orçamento.

- Recebe valores, desconto e quantidade mínima para desconto.
- Calcula o valor total com desconto, se aplicável.
- Apresenta orçamentos e destaca o menor valor.
