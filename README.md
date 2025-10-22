# Projeto: Analista de Dados e Cinema

## Módulo 1: Transposição

Utilizei uma matriz para armazenar as temperaturas, onde cada linha representa uma cidade e cada coluna representa um mês. Para transpor, usei laços aninhados: o laço externo percorre as colunas da matriz original (meses) e o laço interno percorre as linhas (cidades), criando uma nova matriz onde os índices das linhas e colunas são invertidos. Assim, reorganizei os dados para que as linhas representem os meses e as colunas as cidades.

## Módulo 2: Reservas

O mapa de assentos é representado por uma matriz 5x8, onde cada posição é 0 (assento disponível) ou 1 (reservado). As funções de reserva e cancelamento alteram o valor da posição correspondente da matriz: reservar muda de 0 para 1, cancelar de 1 para 0. Isso permite controlar o estado dos assentos de forma direta e eficiente.

## Estratégias Criativas

O uso de vetores e matrizes foi essencial para organizar e manipular dados estruturados em duas dimensões. Matrizes permitem acessar e modificar elementos usando índices claros (linha e coluna), facilitando operações como transposição e controle do mapa de assentos. Usar matrizes é mais eficaz que listas simples, pois modela naturalmente dados bidimensionais, tornando o código mais legível, organizado e eficiente.
