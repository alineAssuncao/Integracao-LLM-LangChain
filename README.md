# 🧠 Integração LLM + LangChain — Fundamentos para Agentes Inteligentes

## 💡 Visão Geral

Este projeto foi desenvolvido como parte dos estudos do curso [Desenvolvimento de Agentes de IA: Do Zero ao Avançado](https://www.udemy.com/course/desenvolvimento-de-agentes-de-ia-do-zero-ao-avancado), ministrado por Rodrigo Macedo e Paulo Andrade, PhD.

O objetivo é demonstrar, por meio de notebooks interativos, como integrar **LLMs (Large Language Models)** com o framework **LangChain**, criando agentes capazes de interpretar comandos, executar tarefas e interagir com ferramentas externas. Os exemplos servem como base para aplicações mais avançadas com LangChain, CrewAI, LangGraph e LlamaIndex.

---

## 🧠 Conceitos Aplicados

- **LLMs**: Modelos de linguagem como GPT que geram respostas com base em contexto  
- **LangChain**: Framework para construção de agentes com memória, ferramentas e raciocínio  
- **Prompt Engineering**: Criação de instruções otimizadas para guiar o comportamento dos agentes  
- **Tools**: Funções externas que os agentes podem acessar para executar tarefas específicas  
- **Chains**: Fluxos de execução que conectam múltiplos componentes de IA

---

## 🛠️ Tecnologias Utilizadas

- `Python`  
- `LangChain`  
- `OpenAI API`  
- `Jupyter Notebook`  
- `dotenv` para variáveis de ambiente  
- `YAML` para configuração modular

---

## ▶️ Como Executar

### ✅ Pré-requisitos
- Python 3.10+
- Jupyter Notebook ou VSCode com suporte a `.ipynb`
- Chave de API (OpenAI ou outro provedor LLM)

### 📦 Ambiente Virtual

```bash
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

Configure o arquivo .env com as suas chaves de API:
```env
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxx
GROQ_API_KEY=gsk_xxxxxxxxxxxxxxxxxxxx
TAVILY_API_KEY=tvly-xxxxxxxxxxxxxxxxxxxx
GEMINI_API_KEY=xxxxxxxxxxxxxxxxxxxx
MISTRAL_API_KEY=xxxxxxxxxxxxxxxxxxxx
COHERE_API_KEY=xxxxxxxxxxxxxxxxxxxx
```

### 📂 Execução dos Notebooks
Abra os arquivos .ipynb com Jupyter ou VSCode e execute célula por célula conforme indicado nos exemplos.


## 📚 Aprendizados
- Integração de LLMs com LangChain
- Criação de agentes com ferramentas e memória
- Estruturação de fluxos com chains e prompts
- Aplicação prática de IA generativa em tarefas reais
- Preparação para projetos multiagente com CrewAI e LangGraph

## 👩‍💻 Autora

Aline Assunção

Engenheira de Qualidade em transição para Inteligência Artificial

📫 [LinkedIn](https://www.linkedin.com/in/alineassuncaoai/)  

📬 aline.jassuncao@gmail.com

>_"A base de um agente inteligente começa com uma integração bem feita entre linguagem e lógica."_


