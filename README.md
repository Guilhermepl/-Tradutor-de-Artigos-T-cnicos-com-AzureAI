# 🧠 Tradutor de Artigos Técnicos com Azure AI

Este projeto faz parte de um desafio da [Digital Innovation One (DIO)](https://www.dio.me/), e tem como objetivo criar um **tradutor de artigos técnicos** utilizando os serviços de **Inteligência Artificial da Azure**.

A solução foi desenvolvida em um **notebook Python**, explorando a API de tradução do Azure para transformar textos técnicos do inglês para o português, preservando a terminologia e o contexto técnico.

---

## 🚀 Objetivo do Projeto

O foco principal é demonstrar o uso prático da **API de Tradução do Azure Cognitive Services** para:
- Traduzir textos técnicos com alta precisão.
- Automatizar o processo de tradução de artigos científicos e tutoriais.
- Mostrar na prática o uso de serviços de IA em aplicações reais.

---

## 🧩 Estrutura do Projeto

```
.
├── scripts/
│   └── tradutor_artigos_tecnicos.ipynb   # Notebook principal do projeto
├── requirements.txt                      # Dependências do projeto
└── README.md                             # Documentação
```

---

## ⚙️ Tecnologias Utilizadas

- 🐍 **Python 3.10+**
- ☁️ **Azure Cognitive Services (Translator Text API)**
- 📓 **Google Colab**
- 📦 Bibliotecas: `requests`, `json`, `pandas`

---

## 🔑 Configuração da Chave da Azure

Para utilizar o tradutor, é necessário ter uma **conta no Azure** e criar um recurso de **Translator**:

1. Crie um recurso no [portal do Azure](https://portal.azure.com/).
2. Vá até o recurso criado → *Keys and Endpoint*.
3. Copie a **Subscription Key** e o **Endpoint**.
4. Defina as variáveis no notebook:
    1. AZURE_TRANSLATOR_KEY
    2. AZURE_TRANSLATOR_ENDPOINT
    3. AZURE_TRANSLATOR_REGION
    4. ZURE_OPEN_AI_KEY

---

## 🧠 Como Executar

Você pode rodar o notebook direto no [Google Colab](https://colab.research.google.com/) sem precisar instalar nada localmente.

1. Acesse o arquivo em [`scripts/tradutor_artigos_tecnicos.ipynb`](scripts/Tradutor_de_Artigos_Técnicos_com_AzureAI.ipynb)
2. Execute as células em sequência.
3. Insira o texto técnico em inglês e veja a tradução automática para português.  

Exemplo:
```python
texto = "Artificial Intelligence is changing how software development is done."
traduzir_texto(texto)
```

Saída esperada:
```
A Inteligência Artificial está mudando a forma como o desenvolvimento de software é feito.
```

---

## 📘 Demonstração

🔗 [Notebook no Google Colab](https://colab.research.google.com/drive/1V2jSojSjRa5fCihi0L-5mJtQSxRGN1om?usp=sharing)

---

## 🧑‍💻 Autor

**Guilherme Pereira Lima**  
Desenvolvedor Full Stack | Entusiasta em IA e Machine Learning  
🌐 [LinkedIn](https://www.linkedin.com/in/guilherme-lima1602/) | 💻 [GitHub](https://github.com/GuilhermePLima)

---

## 🏁 Licença

Este projeto é de uso educacional e foi desenvolvido como parte do programa da [Digital Innovation One (DIO)](https://www.dio.me/).

---

> “O poder da IA está em transformar conhecimento técnico em soluções acessíveis para todos.”
