# 💸 Santas Finanças - App de Organização de Finanças Pessoais

## PRD refinado no Copilot - Prompt inicial submetido ao Lovable
>
```txt
PRD – Aplicativo de Finanças Pessoais Conversacional (com Design Universal)

1. Visão Geral
Criar um aplicativo de finanças pessoais baseado em conversas naturais, acessível para o maior número possível de pessoas. O app deve seguir princípios de design universal, garantindo que diferentes perfis – iniciantes, pessoas com limitações visuais, motoras ou cognitivas – consigam usar o produto sem barreiras.

2. Problema
Apps tradicionais exigem preenchimento manual e navegação complexa. Usuários iniciantes se sentem intimidados. Pessoas com dificuldades de leitura, visão ou atenção encontram barreiras. O desafio é criar uma experiência fluida, inclusiva e acolhedora, centrada em conversa.

3. Público-Alvo
- Iniciantes em organização financeira.
- Pessoas que preferem conversar em vez de preencher formulários.
- Usuários que valorizam simplicidade e acessibilidade.
- Pessoas que se beneficiam de interfaces inclusivas (design universal).

4. Proposta de Valor
Um assistente financeiro conversacional que registra gastos, organiza informações e oferece recomendações personalizadas, com linguagem simples, acessível e adaptável ao estilo do usuário.

5. Funcionalidades-Chave do MVP

5.1. Registro de Gastos via Chat
- O usuário descreve o gasto em linguagem natural.
- O sistema extrai valor, categoria e data automaticamente.
Exemplo: 
Usuário: "Gastei 22 reais no Uber ontem."
App: "Registrei como Transporte. Deseja alterar a categoria?"

5.2. Classificação Automática
- Sugestão de categorias com base no texto.
- Aprendizado contínuo com correções.
Exemplo:
App: "Parece um gasto com Alimentação. Confirmar?"

5.3. Metas Financeiras Simples
- Criar metas básicas.
- Acompanhar progresso via mensagens curtas.
Exemplo:
Usuário: "Quero gastar no máximo 200 reais com delivery este mês."
App: "Meta criada. Avisarei quando estiver perto do limite."

5.4. Agente Financeiro (Dicas e Alertas)
- Sugestões de economia baseadas no comportamento.
- Alertas quando metas estão perto de estourar.
Exemplo:
App: "Você gastou 70% da sua meta de transporte esta semana."

5.5. Relatórios Personalizados
- Resumo semanal e mensal.
- Visualização simples e acessível.
Exemplo:
App: "Seu maior gasto da semana foi Alimentação (R$ 180)."

6. Fluxo Principal do Usuário
1. Onboarding rápido e acessível (linguagem simples, opção de áudio, contraste adequado).
2. Primeira conversa.
3. Registro contínuo via chat.
4. Acompanhamento automático com dicas e relatórios.
5. Ajustes e personalização.

7. Telas do MVP

7.1. Tela de Chat
- Campo de mensagem grande e acessível.
- Histórico claro, com contraste adequado.
- Botões de atalho: "Registrar gasto", "Ver metas", "Relatório rápido".
Exemplo de uso:
Usuário abre o app e vê: "Como posso ajudar hoje?"
Ele digita: "Paguei 50 reais no mercado."

7.2. Tela de Relatórios
- Gráficos simples com opção de texto alternativo.
- Resumo por categoria.
Exemplo:
"Você gastou R$ 1.200 este mês. Maiores gastos: Alimentação (R$ 450), Transporte (R$ 300)."

7.3. Tela de Metas
- Criar, editar e visualizar metas.
- Indicadores visuais simples (barras, porcentagens).
Exemplo:
Meta: "Lazer – limite R$ 200"
Progresso: "R$ 120 (60%)"

7.4. Tela de Configurações
- Preferências de notificação.
- Ajustes de categorias.
- Opções de acessibilidade (tamanho da fonte, contraste, áudio).
Exemplo:
Usuário ativa "Modo de leitura simplificada".

8. Requisitos Técnicos
- NLP para extrair dados de gastos.
- Banco de dados simples para transações e metas.
- Motor de regras para dicas e alertas.
- Backend leve para classificação automática.
- Interface de chat responsiva e acessível.
- Suporte a leitores de tela, contraste alto e navegação simplificada.

9. Critérios de Sucesso
- Registro de gastos sem fricção.
- 80% das transações classificadas automaticamente.
- Relatórios semanais úteis.
- Engajamento de 3 dias na primeira semana.
- Usuários com diferentes perfis conseguem usar o app sem ajuda.

10. Validação Inicial

10.1. Testes com Usuários
- 5 a 10 usuários iniciantes.
- Incluir diversidade de perfis (design universal).

10.2. Métricas
- Número de mensagens enviadas.
- Taxa de correção de categorias.
- Feedback sobre acessibilidade.

10.3. Hipóteses
- Conversa é mais fácil que formulário.
- Dicas aumentam engajamento.
- Relatórios simples bastam.
- Design universal aumenta retenção.

Síntese dos Conceitos

PRD (Product Requirements Document)
Documento que define o que será construído e por que isso importa. Serve como mapa para orientar o desenvolvimento, especialmente em MVPs.

Vibe Coding
Abordagem onde você descreve a intenção, clima e comportamento desejado do produto, e a IA gera código, telas e fluxos coerentes com essa “vibe”.

Design Universal
Princípio de criar produtos que funcionem para o maior número possível de pessoas, independentemente de idade, experiência, limitações físicas, cognitivas ou contexto. Inclui linguagem simples, acessibilidade visual e textual, navegação intuitiva, personalização e suporte a leitores de tela.

```
## Interações com o Lovable
Crie um APP de Finanças Pessoais com base no seguinte PRD (Product Requirements Document): {PRD}

Adicione controle de usuários ao APP incluindo interface de cadastramento e login. Além disso, ao registrar despesas, a tela não faz scroll automatico para que a janela de prompt fique sempre visível. Ajuste a interface para fazer scroll de registros para manter o campo de prompt visível.

OK. Criei monta com email e senha para acessar o APP, entretanto, ao entrar, o APP não sai da tela de login, ficando sempre na mesma tela de login. Favor verificar e corrigir de modo que ao fazer o login, o app apresente a sua interface inicial.

Melhore a interface inicial incluindo cards de receitas, despesas, saldo e metas. No relatório mensal, inclua também o saldo no resumo inicial, ao lado de receitas e despesas.

Perfeito! Só não gostei do nome do AAP(Bento). Pode trocar para Santas Finanças?

## Resaultado Final no Lovable

Site https://santas-financas.lovable.app/

### Tela inicial - Login e Criar Conta

<img width="1248" height="856" alt="image" src="https://github.com/user-attachments/assets/3cb283ec-4f34-4bfd-a900-3e45ec0a251d" />

### Tela de Interação com o Chat - Registo de movimentações e menu

<img width="1245" height="855" alt="image" src="https://github.com/user-attachments/assets/96b8efd4-6c56-4cd7-ae86-02b827cb7b75" />

### Metas

<img width="1247" height="858" alt="image" src="https://github.com/user-attachments/assets/8361861d-09fa-4c61-8a21-9e1933ba357f" />

### Relatório Mensal

<img width="1251" height="858" alt="image" src="https://github.com/user-attachments/assets/c4730085-fb08-4367-85e5-069e9ebeb745" />

## Resumo das Funcionalidades do Santas Finanças

### Visão Geral
O Santas Finanças é um aplicativo de organização financeira baseado em conversa. Ele permite registrar gastos, acompanhar receitas, visualizar saldo, criar metas e receber análises — tudo em linguagem natural e com princípios de design universal.

---
### Registro de Gastos e Receitas por Chat
- O usuário informa um gasto ou receita em linguagem natural.
- O sistema interpreta automaticamente valor, categoria e data.
- Exemplos:
  - "Gastei 22 reais no Uber ontem"
  - "Recebi meu salário de 3500"

### Classificação Automática
- O app identifica a categoria mais provável para cada transação.
- O usuário pode confirmar ou corrigir, permitindo aprendizado contínuo.

### Painel Financeiro
- Exibe valores de:
  - Receitas
  - Despesas
  - Saldo
  - Metas
- Os valores são atualizados conforme o usuário interage via chat.

### Metas Financeiras
- O usuário cria metas usando linguagem natural.
- Exemplo:
  - "Quero gastar no máximo 200 com delivery este mês"

### Relatórios e Perguntas Inteligentes
- O usuário pode solicitar análises rápidas.
- Exemplo:
  - "Como estou indo este mês?"

### Interface Conversacional
- Chat como principal forma de interação.
- Sugestões rápidas de mensagens.
- Campo de entrada com exemplo: "Conta pra mim... ex: gastei 30 no almoço."

### Design Universal
- Linguagem simples e direta.
- Interface limpa e de alto contraste.
- Navegação centrada em conversa.
- Ideal para iniciantes ou pessoas que preferem interações naturais.

### Fluxo Básico de Uso
1. O usuário abre o app e vê seu painel financeiro.
2. O assistente inicia a conversa e pede o primeiro gasto.
3. O usuário registra gastos ou receitas via chat.
4. O sistema atualiza automaticamente receitas, despesas e saldo.
5. O usuário pode criar metas ou pedir relatórios.
6. O app responde com análises simples e personalizadas.


## Reflexões

### O que funcionou bem?
O refinamento do PRD prévio, fornecido pelo professor no repositório copiado (fork), por meio do Copilot funcionou a contento, embora, provavelmente em função da minha inexperiência, tenha sido necessário fazer mais de 5 interações.

### O que não funcionou como esperado?
A primeira versão gerada pelo Lovable não incluiu o controle de acesso (Auth) para cadastro e login de usuários do novo APP.
Feita nova interação com o Lovable para implementar o Auth, a mesma não funcionou corretamente, me obrigando a mais uma interação e consequente gasto de créditos.
Solicitei a criação de cards de resumo das despesas, receitas, saldo e metas na tela inicial. Ele criou, mas me parecem muito elementares.

### O que aprendeu sobre conversar com IAs?
Aprendi que tenho muito a aprender sobre como estruturar e elaborar meus prompts para ter bons resultados desde as primeiras interações. Minha fragilidade neste sentido pode me custar o consumo rápido e ineficiente dos meus créditos.


