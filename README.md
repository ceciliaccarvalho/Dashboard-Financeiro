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
 
## Como usar

1. **Baixe os arquivos** do repositório: `dashboard-mirante-forneria-local.html` e `modelo-dados-dashboard.xlsx`.
2. **Preencha a planilha** com os seus números. As abas são `Config`, `A Receber`, `A Pagar`, `Despesas por Categoria` e `Evolução` (um dia por linha, de segunda a sexta). Os valores que já estão nela são só exemplos.
3. **Abra o HTML** no navegador (duplo clique no arquivo).
4. **Clique em "Carregar planilha"** e escolha o arquivo `.xlsx`. Os cartões, a tabela e os gráficos são atualizados automaticamente.
5. **Para enviar à gestão**, use `Ctrl+P` (ou `Cmd+P` no Mac) e escolha "Salvar como PDF".

### Dicas
- Não renomeie as abas nem os cabeçalhos da linha 1, e não deixe linhas em branco no meio das tabelas.
- Você pode usar fórmulas no Excel. Salve o arquivo antes de carregar e garanta que as células de valor devolvam números.
- Não use senha na planilha, porque o dashboard não consegue abrir arquivos protegidos.
- Mantenha um lançamento por linha;
- Use sempre o mesmo padrão de datas e de categorias.
---
 
## 🔌 Integração com o ERP (opcional)
 
Digitar dados todo dia dá trabalho. Por isso, existe a possibilidade de **"conectar" a planilha de base de dados com a base principal da empresa (o ERP)**, para que as informações cheguem de forma automática ou semiautomática. Assim, o dashboard se mantém atualizado sem depender de lançamento manual.
 
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
 
Você pode adaptar o dashboard a sua empresa:
 
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
 
Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
 
## 👩‍💻 Autoria
 
Criado por **Cecilia C. Carvalho**.
