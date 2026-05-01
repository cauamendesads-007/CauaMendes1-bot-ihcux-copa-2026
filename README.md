# ihcux-copa-2026

##  Instituição

Centro Universitário UNA (Barreiro)



##  Integrantes

* Cauã Mendes - Análise e Desenvolvimento de Sistemas


---

##  Problema Focado

O projeto busca resolver a dificuldade do torcedor em:

* Pedir alimentos durante o jogo sem perder lances importantes
* Acompanhar replays de momentos relevantes da partida
* Navegar por opções de forma rápida dentro de um ambiente movimentado (estádio)

A principal dor priorizada foi:
 **Evitar que o torcedor perca momentos do jogo ao realizar ações paralelas (como comprar comida).**

---

##  Justificativa de Design

O design foi pensado para ser **rápido, direto e funcional**, considerando o contexto de uso (estádio, distrações, pressa).

Principais decisões:

*  **Tela inicial simples:** acesso rápido às funções principais
*  **Organização por etapas:** o usuário segue um fluxo claro (seleção → pedido → confirmação)
*  **Listas objetivas:** itens com nome, preço e controle de quantidade
*  **Botões grandes e visíveis:** facilitam uso em ambientes com pouca atenção
*  **Separação de funcionalidades:** comida e replay não se misturam, evitando confusão

Tudo foi estruturado para reduzir esforço cognitivo e acelerar ações.

---

##  Fluxo do Usuário

###  Pedido de Lanche

1. Usuário acessa o app (Tela 1)
2. Seleciona a opção de alimentos (Tela 2)
3. Visualiza o cardápio (Tela 3)
4. Escolhe itens e quantidades (Tela 4)
5. Finaliza o pedido

✔ Resultado: pedido feito sem sair do lugar e sem perder o jogo

---

###  Ver Replay

1. Usuário acessa a opção de replay (Tela 5)
2. Seleciona o momento desejado
3. Assiste ao replay diretamente no app (Tela 6)

✔ Resultado: consegue rever jogadas importantes rapidamente

---

##  Tecnologia Utilizada

* Figma (protótipo das telas)
* Conceitos de UX/UI Design
* Estrutura pensada para implementação em Blazor WebAssembly (.NET)


---

## Heurística – Ajuda e Documentação

Mesmo sendo intuitivo, o sistema segue a heurística de **Ajuda e Documentação**:

* Interface clara e autoexplicativa
* Navegação simples e previsível
* Informações diretas e organizadas
* Usuário entende rapidamente como usar sem precisar de instruções externas

Isso garante facilidade de uso mesmo em situações rápidas e dinâmicas como em um estádio.

---

## obs;

Este projeto foi desenvolvido com foco em melhorar a experiência do torcedor, unindo praticidade e acesso rápido a funcionalidades essenciais durante eventos esportivos.
