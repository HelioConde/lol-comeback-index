<div align="center">
  <h1>🧪 LoL Comeback Index</h1>
  <p><strong>Estudo para identificar viradas a partir de dados verificáveis de partidas e comparar contextos, sem inventar uma pontuação de recuperação.</strong></p>
  <p><img alt="Status" src="https://img.shields.io/badge/status-concep%C3%A7%C3%A3o-64748b"></p>
</div>

> **Projeto em concepção — documentação apenas.** O repositório ainda não contém frontend, backend ou aplicativo executável. O fluxo abaixo é um plano de produto, não uma funcionalidade disponível.

## Problema

O resultado final não explica quando uma equipe esteve em desvantagem nem como recuperou o controle do jogo.

## Experiência proposta

Selecionar uma partida → verificar quais séries temporais existem → identificar possíveis pontos de desvantagem/recuperação → revisar a conclusão.

## Dados mínimos do primeiro protótipo

ID da partida, linha do tempo disponível, diferença temporal de recursos/objetivos, resultado e evidências da classificação.

## MVP planejado

Definir e testar uma regra de virada sobre um pequeno conjunto de timelines válidas, exibindo também os casos inconclusivos.

**Critério para considerar o MVP útil:** Cada classificação pode ser reproduzida a partir dos eventos usados e mostra claramente quando faltam dados.

## Limites e dependências

Placar final, KDA e ouro final sozinhos não provam uma virada. A cobertura e a granularidade da timeline Riot precisam ser verificadas.

A implementação deve começar com **dados demonstrativos identificados e armazenamento local**, se adequado. Integrações externas, autenticação e anúncios exigem revisão própria; não serão anunciados como funcionais antes de existirem.

## Próximo passo

1. Desenhar uma tela com o fluxo principal.
2. Implementar um protótipo pequeno que funcione no celular.
3. Testar navegação, salvar/recuperar dados e tratamento de casos vazios.
4. Pedir feedback de usuários antes de ampliar o escopo.

## Projetos relacionados

Este conceito faz parte do [Ideias IA Lab](https://github.com/HelioConde/ideias-ia-lab). Explore [outros repositórios de Hélio Conde](https://github.com/HelioConde?tab=repositories).

*League of Legends pertence aos seus respectivos titulares. Projeto independente, sem afiliação oficial.*

Autor: [Hélio Conde](https://github.com/HelioConde).
