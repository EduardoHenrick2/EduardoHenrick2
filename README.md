<div align="center">
# Eduardo Henrick Souza Lopes
 
**Estudante de Análise e Desenvolvimento de Sistemas · Software com foco em IA generativa**
 
Betim, MG · Buscando estágio em Engenharia de Software com foco em IA
 
[LinkedIn](https://www.linkedin.com/in/eduardo-henrick-souza-lopes-7b56b6360) · [eduardohenrick900@gmail.com](mailto:eduardohenrick900@gmail.com)
 
</div>
---
 
## Sobre mim
 
Estudo **Análise e Desenvolvimento de Sistemas na PUC Minas** (conclusão prevista em dez/2027) e tenho formação técnica em Informática. Gosto de construir ferramentas a partir de problemas reais que vi no dia a dia. Trabalhei em uma oficina de motos, vi o trabalho de ordens de serviço feito à mão e comecei a construir uma solução com IA para isso.
 
Hoje o meu foco é **integrar LLMs em software de forma confiável**: validar o que o modelo responde, versionar prompts e medir o resultado com casos de teste, em vez de confiar só em "parece que funciona".
 
- Back-end com **C# e ASP.NET Core**, e também JavaScript/TypeScript
- Integração de LLM (**Google Gemini API**) em APIs e fluxos de automação
- Modelagem de banco de dados e de processos (BPMN)
- Imersão em Dados e IA (Santander Open Academy), em andamento
---
 
## Projetos em destaque
 
### OS Triage: do relato do cliente à ficha de serviço
 
Fluxo com LLM que transforma o relato livre de um cliente de oficina de motos em uma ficha de serviço estruturada.
 
```mermaid
flowchart LR
    A[Relato livre do cliente] --> B[LLM · Gemini API]
    B --> C[Validação em código<br/>esquema, categoria, campos obrigatórios]
    C --> D[Regra de urgência<br/>palavra de risco eleva a urgência]
    D --> E[Ficha de serviço estruturada]
```
 
- Prompts versionados e **avaliados em 24 casos de teste com gabarito**
- A validação em código evita aceitar respostas fora do formato esperado
- Stack: `n8n` `Google Gemini API` `JavaScript` `Docker`
- Repositório: [OS-Triage](https://github.com/EduardoHenrick2/OS-Triage)
### OS Triage API
 
API que serve de base para o fluxo acima: recebe requisições REST e mensagens de bots de mensageria, com processamento por IA, para a triagem e a entrada de ordens de serviço.
 
- Ambiente containerizado com Docker Compose, scripts de inicialização do banco e testes unitários
- Stack: `C#` `.NET` `PostgreSQL` `Docker`
- Repositório: [OS-Triage_API](https://github.com/EduardoHenrick2/OS-Triage_API)
### Green Estoque
 
Sistema full-stack de controle de estoque para a **Green Volt** (energia solar), projeto de extensão na PUC Minas, em equipe interdisciplinar de 10 pessoas.
 
- Minha atuação: back-end (Node.js/Express), modelagem do banco (Prisma/PostgreSQL), modelagem de processos em BPMN e documentação
- Planejamento de uma API com nove módulos e esquema de seis tabelas
- Stack: `React` `Node.js` `Express` `Prisma` `PostgreSQL`
- Repositório: [green-estoque-TAIPN](https://github.com/EduardoHenrick2/green-estoque-TAIPN)
---
 
## Stack
 
| Área | Tecnologias |
|---|---|
| Linguagens | C#, JavaScript, TypeScript, SQL |
| Back-end | ASP.NET Core, Node.js, Express, Prisma, APIs REST |
| Front-end | React, HTML, CSS, Tailwind CSS, Vite |
| Bancos de dados | PostgreSQL, MySQL |
| IA generativa | Google Gemini API, engenharia de prompts, n8n |
| Ferramentas | Git, GitHub, Visual Studio, VS Code, Figma, Bizagi Modeler |
 
---
 
## Estudando agora
 
- **Python**, para trabalhar melhor com dados e avaliação de modelos
- **Testes automatizados em C#**
- **Docker**, indo além do básico
- Integração de LLMs em APIs de forma mais robusta
---
 
## Outros repositórios
 
- [Galeria Sonora](https://github.com/EduardoHenrick2/Galeria-Sonora)
- [Atividades em C#](https://github.com/EduardoHenrick2/Atividades-em-C-): exercícios de lógica e algoritmos
---
 
<div align="center">
Quer conversar sobre software, IA ou oportunidades de estágio? Me chama no [LinkedIn](https://www.linkedin.com/in/eduardo-henrick-souza-lopes-7b56b6360) ou por [e-mail](mailto:eduardohenrick900@gmail.com).
 
</div>
