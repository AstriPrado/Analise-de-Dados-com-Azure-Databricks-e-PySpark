
# 🚀 Projeto de Análise de Dados com Azure Databricks e Spark

Este projeto foi desenvolvido como parte do **Bootcamp Microsoft AI - Azure Databricks**. O objetivo é provisionar um ambiente Databricks no portal Azure, criar um cluster e utilizar o **Spark** para realizar uma análise de dados.

---

## 🔧 Etapas do Projeto

### 1️⃣ Provisionando o Azure Databricks

- Acesse o portal do [Azure](https://portal.azure.com).
- Busque por **Databricks** no menu de recursos.
- Clique em **Criar** e preencha as informações necessárias.
- Clique em **Revisar + Criar** e depois em **Criar**.

![Criação do recurso no Azure](./imagens/imagem_1.png)

---

### 2️⃣ Acessando o Workspace do Databricks

- Após a implantação, clique em **Ir para o recurso**.
- Selecione **Iniciar workspace** para abrir o ambiente do Databricks.

![Acessando workspace](./imagens/imagem_2.png)

---

### 3️⃣ Criando um Cluster (Versão Community)

- No menu lateral, clique em **Compute** ou **Clusters**.
- Clique em **Create Compute**.
- A versão **Community** tem limitações, mas atende bem para projetos de estudo.

![Criação do Cluster - parte 1](./imagens/imagem_3.png)
![Criação do Cluster - parte 2](./imagens/imagem_4.png)

---

### 4️⃣ Criando um Notebook

- Crie um Notebook ao subir o arquivo CSV para análise.
- Dataset utilizado: **Análise de Vendas**.

![Criação do Notebook](./imagens/imagem_5.png)

---

## 🔍 Análise de Dados com PySpark

- 🔸 **Leitura do arquivo CSV**
- 🔸 **Análise das Vendas por Produto**
- 🔸 **Análise das Vendas por Cidade**
- 🔸 **Análise das Vendas por Forma de Pagamento**
- 🔸 **Evolução das Vendas por Mês**

![Código de leitura](./imagens/imagem_6.png)
![Análise Produto](./imagens/imagem_7.png)
![Análise Cidade](./imagens/imagem_8.png)
![Análise Forma de Pagamento e Evolução](./imagens/imagem_9.png)

---

## 🧠 Tecnologias e Ferramentas

- 🔹 Microsoft Azure
- 🔹 Azure Databricks
- 🔹 Apache Spark
- 🔹 PySpark
- 🔹 Python
- 🔹 Git & GitHub

---

## 👩‍💻 Autor(a)

Desenvolvido por **Astri** — [@SeuUsuarioGitHub](https://github.com/SeuUsuarioGitHub)  
Projeto realizado como parte do **Bootcamp Microsoft AI - Azure Databricks**.

---

## 📁 Estrutura de Pastas Sugerida

```
📦 Projeto-Databricks-Spark
├── imagens
│   ├── imagem_1.png
│   ├── imagem_2.png
│   ├── imagem_3.png
│   ├── imagem_4.png
│   ├── imagem_5.png
│   ├── imagem_6.png
│   ├── imagem_7.png
│   ├── imagem_8.png
│   ├── imagem_9.png
├── dataset
│   └── vendas.csv
├── notebook
│   └── analise-vendas.ipynb
├── README.md
```

---

## ✅ Observações

- Optei por incluir apenas os prints dos códigos no README para mantê-lo mais leve e objetivo.
- A análise foi realizada na versão **Community** do Databricks, mas o README traz também o passo a passo para configuração via Azure.
