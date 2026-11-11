# 📊 Dashboard Financeiro para Restaurantes
 
Um painel visual, simples e fácil de entender para a gestão de restaurantes acompanharem a **saúde financeira da empresa ao longo da semana**, tanto por **competência** quanto por **fluxo de caixa**.
 
<img width="1017" height="914" alt="image" src="https://github.com/user-attachments/assets/6e2a027b-bce7-4465-ae39-76b5643276cd" />

---
 
## 🎯 Para que serve
 
Muitos restaurantes têm os números espalhados entre sistema de gestão (ERP), planilhas e anotações, e a gestão acaba sem uma visão rápida de como o negócio está indo. Este projeto nasceu para resolver isso com uma **solução visual, rápida de colocar no ar** e que qualquer pessoa da gestão consiga ler sem treinamento.
 
Com ele é possível acompanhar, de forma semanal:
 
- Entradas e saídas (visão de **fluxo de caixa**);
- Receitas e despesas no período em que foram geradas (visão de **competência**);
- A evolução da saúde financeira do restaurante ao longo das semanas.
---
 
## 📁 O que tem neste repositório
 
| Arquivo | Descrição |
|---|---|
| `DashBoard-Lanchonete.html` | O dashboard (abre direto no navegador). |
| `modelo-base-de-dados.xlsx` | Planilha modelo com a estrutura da base de dados que alimenta o dashboard. |
 
---
 
## 🚀 Como usar
 
1. **Baixe** os dois arquivos deste repositório (botão verde **Code → Download ZIP**).
2. **Preencha** a planilha `modelo-base-de-dados.xlsx` com os dados do seu restaurante, respeitando as colunas do modelo.
3. **Conecte os dados ao dashboard** conforme o formato de leitura configurado no arquivo HTML.
4. **Abra** o `DashBoard-Lanchonete.html` no navegador (Chrome, Edge, Firefox ou Safari) e acompanhe os indicadores.
> 💡 Se o dashboard abrir em branco, confira se os nomes das colunas e das abas da planilha continuam iguais aos do modelo e se as datas estão no formato correto.
 
---
 
## 🗂️ Base de dados (planilha)
 
A planilha é a "fonte da verdade" do dashboard: tudo o que aparece nos gráficos e tabelas vem dela.
 
**Dica importante:** a planilha pode ser **personalizada com fórmulas**, para que você não precise atualizar tudo manualmente. Por exemplo, totais, categorias e cálculos de período podem ser feitos automaticamente a partir dos lançamentos.
 
Recomendações:
 
- Não renomeie abas e colunas usadas pelo dashboard;
- Mantenha um lançamento por linha;
- Use sempre o mesmo padrão de datas e de categorias.
---
 
## 🔌 Integração com o ERP (opcional)
 
Digitar dados todo dia dá trabalho. Por isso, existe a possibilidade de **"conectar" a planilha de base de dados com a base principal do restaurante (o ERP)**, para que as informações cheguem de forma automática ou semiautomática. Assim, o dashboard se mantém atualizado sem depender de lançamento manual.
 
A ideia inicial do projeto, porém, era **desenvolver rapidamente uma solução visual** para a gestão acompanhar a saúde financeira. A integração é um passo seguinte, para quem quiser evoluir a ferramenta.
 
---
 
## 🛠️ Como foi desenvolvido
 
O projeto foi construído em etapas, combinando entendimento do negócio, design e inteligência artificial:
 
1. **Definição dos dados mais importantes.** Antes de qualquer tela, o primeiro passo foi decidir quais informações a gestão realmente precisa ver para entender a saúde financeira do restaurante, sem excesso de números.
2. **Escolha da forma de exibição.** Para cada dado, foi definido como ele seria apresentado: gráfico, tabela, indicador em destaque etc., sempre pensando em leitura rápida e fácil.
3. **Base visual no Figma.** A estrutura inicial do layout foi criada com ajuda do **Figma**.
4. **Código com o Claude.** O layout foi enviado ao **Claude (Anthropic)**, que escreveu o código principal do dashboard e as integrações com a planilha.
---
 
## 🧰 Tecnologias
 
- HTML, CSS e JavaScript
- Excel (`.xlsx`) como base de dados
- Figma (design)
- Claude (desenvolvimento do código com apoio de IA)
---
 
## 🎨 Personalização
 
Você pode adaptar o dashboard ao seu restaurante:
 
- Nome do estabelecimento, cores e logotipo;
- Categorias de receitas e despesas;
- Indicadores e gráficos exibidos.
---
 
## 🔒 Privacidade
 
Este repositório é público. **Não envie dados reais e sensíveis** do seu restaurante (faturamento, fornecedores, funcionários) para cá. Use dados fictícios ou mantenha a versão com dados reais em um local privado.
 
---
 
## 🗺️ Próximos passos (ideias)
 
- [ ] Conexão automática com o ERP
- [ ] Planilha online com atualização em tempo real
- [ ] Novos indicadores e comparativos entre semanas
---
 
## 📄 Licença
 
*Defina aqui a licença do projeto (por exemplo, MIT).*
 
## 👩‍💻 Autoria
 
Criado por **Cecilia C. Carvalho**.
