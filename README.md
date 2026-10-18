
# Controle de Níveis de Água

## Descrição do Projeto

Este projeto foi desenvolvido como parte da atividade de **Bibliotecas em Python**, do curso Técnico em Desenvolvimento de Sistemas da ETEC.

O objetivo é simular um sistema de monitoramento dos níveis de água de um reservatório, utilizando a linguagem Python e a biblioteca **Colorama** para exibir mensagens coloridas no terminal.

O sistema apresenta cinco níveis de água, permitindo identificar visualmente a situação do reservatório, desde um nível crítico até um nível muito alto.

## Funcionalidades

- Monitoramento simulado de cinco níveis de água.
- Utilização de listas para armazenar as informações.
- Função para definir as cores conforme o nível.
- Exibição de mensagens coloridas no terminal.
- Restauração automática da cor padrão do terminal.
- Código simples, organizado e de fácil compreensão.

## Classificação dos Níveis

| Nível | Situação | Cor |
|---|---|---|
| 1 | Muito baixo (crítico) | Vermelho |
| 2 | Baixo | Amarelo |
| 3 | Médio | Verde |
| 4 | Alto | Ciano |
| 5 | Muito alto (alerta) | Azul |

## Tecnologias Utilizadas

- **Python:** linguagem utilizada para desenvolver o sistema.
- **Colorama:** biblioteca responsável por adicionar cores às mensagens do terminal.
- **Git e GitHub:** ferramentas utilizadas para versionamento e armazenamento do projeto.

## Como Executar

**1. Clone o repositório:**

```bash
git clone https://github.com/cauareiis/controle-niveis-agua.git
```

**2. Acesse a pasta do projeto:**

```bash
cd controle-niveis-agua
```

**3. Instale a biblioteca Colorama:**

```bash
pip install colorama
```

**4. Execute o programa:**

```bash
python app.py
```

## Como o Sistema Funciona

O programa utiliza uma lista para representar os cinco níveis do reservatório.

Uma função identifica o nível informado e associa uma cor à mensagem correspondente, utilizando a biblioteca Colorama.

Durante a execução, o sistema apresenta as situações do reservatório no terminal, destacando cada nível com sua respectiva cor.

Após a exibição, a formatação padrão do terminal é restaurada.

## Objetivo da Atividade

Com esta atividade, busquei colocar em prática os conhecimentos adquiridos sobre listas, funções e bibliotecas em Python.

Além disso, pude compreender como a utilização de cores pode facilitar a interpretação de informações em sistemas de monitoramento.

## Competências Desenvolvidas

- Aplicação de programação estruturada.
- Utilização de listas e funções.
- Importação de bibliotecas externas.
- Organização e legibilidade do código.
- Versionamento de projetos com Git e GitHub.

## Autor

**Cauã Barbosa**

Estudante do curso Técnico em Desenvolvimento de Sistemas — ETEC.

GitHub: [@cauareiis](https://github.com/cauareiis)

---

Projeto desenvolvido para fins educacionais.