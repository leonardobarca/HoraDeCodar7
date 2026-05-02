# Arquitetura do Sistema

O sistema é dividido em dois arquivos independentes, cada um responsável por um conjunto de funcionalidades.

**hotel.html** contém o menu principal e os seguintes módulos:
- Reserva de quartos
- Eventos
- Ar-condicionado
- Abastecimento de carros
- Relatórios operacionais

**cadastroHospedes.html** contém o módulo de cadastro de hóspedes, com as operações de cadastrar, pesquisar, listar, atualizar e remover.

Cada funcionalidade é implementada como uma função isolada, sem dependências externas.
Os dados são mantidos em memória durante a execução via variáveis globais declaradas no topo de cada arquivo.