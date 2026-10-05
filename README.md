# &#x20; Automação de Cadastro de Produtos com Python

> Projeto de estudo realizado durante o \*\*Intensivão de Python da Hashtag Treinamentos\*\*.

## &#x20; Sobre o projeto

Este projeto demonstra como utilizar Python para automatizar uma tarefa operacional repetitiva: o cadastro de produtos em um sistema web.

A aplicação lê os dados de uma base de produtos e utiliza automação de interface para preencher os campos e realizar os cadastros.

O objetivo principal foi praticar a aplicação de Python em um cenário de **automação de processos**, combinando manipulação de dados e interação com uma aplicação.

## &#x20; Tecnologias utilizadas

* **Python**
* **Pandas** — leitura e manipulação da base de dados
* **PyAutoGUI** — automação de teclado e mouse

## &#x20; Fluxo da automação

```text
Base de produtos
       ↓
Leitura com Pandas
       ↓
Percorrer os registros
       ↓
Automação da interface
       ↓
Preenchimento dos campos
       ↓
Cadastro dos produtos
```

## &#x20; Conceitos praticados

* Leitura e manipulação de dados com Pandas
* Estruturas de repetição
* Variáveis e estruturas de dados
* Automação de tarefas repetitivas
* Interação com aplicações por teclado e mouse
* Tratamento básico de dados antes da automação

## &#x20; Como executar

### 1\. Clone o repositório

```bash
git clone [https://github.com/samuelsilva-data7/automacao-cadastro-produtos-python]
cd automacao-cadastro-produtos-python
```

### 2\. Instale as dependências

```bash
pip install -r requirements.txt
```

### 3\. Configure os dados de acesso

Antes de executar, substitua os placeholders existentes no código pelos seus dados locais:

```python
SEU\_EMAIL\_AQUI
SUA\_SENHA\_AQUI
```


### 4\. Execute

```bash
python automacao\_produtos.py
```

> Como o projeto utiliza automação de interface, o comportamento pode depender da resolução da tela, navegador e ambiente utilizados.

## &#x20; Aprendizado

Este projeto fez parte da minha formação prática em Python e foi importante para entender como programação pode ser aplicada à **automação de processos e redução de tarefas manuais**.

## &#x20; Próximas melhorias

Algumas evoluções que pretendo estudar para tornar a solução mais robusta:

* adicionar tratamento de exceções;
* criar logs de execução;
* validar os dados antes do cadastro;
* separar configurações da lógica da aplicação;
* substituir coordenadas fixas por uma automação mais robusta;
* adicionar relatórios de sucesso e falha.



**Samuel Fernandes**  
Estudante de Ciência da Computação | Python • SQL • Dados • Automação

