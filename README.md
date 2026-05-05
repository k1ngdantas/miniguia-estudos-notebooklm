# Miniguia de Estudos: IA Generativa e Engenharia de Prompts 🤖

## 🎯 Contexto e Objetivos
Este repositório contém um material de estudo estruturado sobre como as IAs Generativas funcionam e as melhores práticas para criar comandos (prompts) eficazes. O objetivo é servir como um guia rápido para iniciantes que desejam melhorar a precisão das respostas obtidas por modelos como GPT e Gemini.

## 📚 Curadoria de Fontes
As fontes abaixo foram inseridas no NotebookLM para gerar o conhecimento base:
1. [Guia de Engenharia de Prompt da OpenAI](https://openai.com)
2. [O que é IA Generativa? - Google Cloud](https://google.com)
3. [Artigo: O papel dos Transformers na IA moderna](https://wikipedia.org)

## 🧠 Engenharia de Prompts e "Cicatrizes"

### Estratégias Testadas:
- **Zero-Shot:** "Explique o que é um prompt." -> *Resposta genérica.*
- **Persona/Role Prompting:** "Atue como um Professor de Tecnologia e explique o que é um prompt para uma criança de 10 anos." -> *Resposta muito mais clara e didática.*

### Dificuldades Encontradas (Troubleshooting):
- **Alucinação:** Em um dos testes, a IA inventou uma técnica de prompt que não existia nas fontes. 
- **Solução:** Ajustei o prompt para: "Baseie-se **apenas** nos documentos fornecidos. Se a informação não estiver lá, diga que não sabe." Isso resolveu o problema imediatamente.

## 📖 Miniguia de Estudo (Entrega Final)

### Resumo Estruturado
A IA Generativa utiliza modelos estatísticos (Transformers) para prever a próxima palavra em uma sequência. A qualidade da resposta depende diretamente do contexto fornecido no prompt.

### Glossário de Conceitos
- **LLM (Large Language Model):** Modelos treinados em enormes volumes de texto.
- **Tokens:** Unidades de texto (pedaços de palavras) que a IA processa.
- **Janela de Contexto:** O limite de "memória de curto prazo" da IA durante uma conversa.

### Prompts Reutilizáveis
- `Para Resumos:` "Resuma o documento X em 5 pontos-chave voltados para um gestor de projetos."
- `Para Testes:` "Com base na fonte Y, crie 3 perguntas difíceis para testar meu conhecimento sobre arquitetura de sistemas."
