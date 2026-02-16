# 🎮 Dashboard de Vendas - Xbox Game Pass

Este projeto foi desenvolvido como parte do desafio de projeto da **DIO (Digital Innovation One)** na trilha de Excel. O objetivo foi transformar uma base de dados bruta de vendas de assinaturas em um **Dashboard Gerencial** visual e interativo para tomada de decisão.

## 📝 Descrição do Projeto

O projeto consiste na análise de vendas de assinaturas do serviço **Xbox Game Pass**. A partir de uma base de dados contendo informações de assinantes, tipos de planos (Core, Standard, Ultimate) e receitas adicionais (EA Play, Minecraft), foi construído um painel para monitorar o faturamento e o comportamento dos consumidores.

O dashboard foca na resposta rápida a perguntas de negócio, utilizando elementos visuais alinhados à identidade visual da marca (Paleta de cores Xbox).

## 📊 Perguntas de Negócio Respondidas

A ferramenta foi estruturada para responder às seguintes questões estratégicas (presentes na aba de *Cálculos*):

1.  **Faturamento Total:** Qual a receita global gerada pelas assinaturas?
2.  **Análise por Tipo de Plano:** Comparativo de receita entre planos Anuais, Mensais e Trimestrais.
3.  **Impacto da Renovação Automática:** Quanto da receita vem de assinaturas com auto-renovação ativada vs. desativada?
4.  **Receita de Adicionais (Add-ons):**
    * Vendas de *EA Play Season Pass*.
    * Vendas de *Minecraft Season Pass*.

## 🚀 Funcionalidades e Recursos

* **Segmentação de Dados (Slicers):** Filtros interativos que permitem alternar a visualização por período (Trimestral/Mensal) ou tipo de plano.
* **Design de Interface (UI):**
    * Uso da paleta de cores oficial (Verde Xbox: `#9BC848`, `#22C55E`).
    * Background limpo e organização por cartões (Cards).
* **Tratamento de Dados:**
    * Cálculo de valores totais considerando cupons de desconto e preços de passes de temporada.
    * Estruturação de Tabelas Dinâmicas para consolidação dos dados.

## 📂 Estrutura do Arquivo

O arquivo Excel está organizado em abas para facilitar a manutenção e escalabilidade:

1.  **Dashboard:** A interface final para o usuário (Front-end).
2.  **Bases:** A base de dados bruta contendo ID do assinante, datas, planos e valores.
3.  **Cálculos:** Tabelas dinâmicas e células de apoio que alimentam os gráficos.
4.  **Assets:** Referências visuais, códigos hexadecimais de cores e ícones utilizados.

## 🛠️ Tecnologias Utilizadas

* **Microsoft Excel:**
    * Tabelas Dinâmicas (Pivot Tables).
    * Gráficos Dinâmicos.
    * Funções de Data e Texto.
    * Formatação Condicional e Design de Painéis.

## 👱 Autor

**Vinicius Lordaro**

---

*Projeto desenvolvido para o Bootcamp da DIO.*
