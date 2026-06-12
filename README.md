Sistema de Dicionário com Tabela Hash em C

Este projeto consiste em um sistema de dicionário desenvolvido em linguagem C utilizando a estrutura de dados de Tabela Hash com tratamento de colisões por meio de Listas Encadeadas.

Tecnologias e Conceitos Implementados Linguagem C: Construção limpa e modular. Alocação Dinâmica: Uso estratégico malloc()e free()para gerenciar nós na memória. Ponteiros e Structs: Estruturação dos dados da palavra, definição e encadeamentos de referências. Encadeamento Separado: Resolução eficiente de colisões em tempo de execução.

Funcionalidades do Sistema

Inserir palavras e definições**: Adicionados termos ao dicionário. Se a palavra já existir, atualize sua definição.
Buscar palavras: Localização rápida utilizando a indexação direta do cálculo hash.
Remover palavras: Remover o nó da memória dinâmica e costurar as referências dos ponteiros adjacentes.
Exibir tabela: Uma visão gráfica textual mostrando o estado atual das posições (índices) da tabela.
Estatísticas Completas: Total de elementos inseridos. Total de colisões mapeadas. Fator de carga da tabela (
α
=
elementos
grupo
). Tamanho da maior lista encadeada encontrada.
