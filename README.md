# 🚀 Copiloto de IA para Análise Estratégica Automatizada de Documentos de RH

**Visão geral do projeto**

<img width="1920" height="1080" alt="Make customers aware of your brand or product  (1)" src="https://github.com/user-attachments/assets/d9070a0d-c209-4678-8725-6ba18fa3e549" />


### 📌 Descrição do Projeto

Este projeto apresenta o desenvolvimento de um assistente inteligente baseado em IA Generativa, capaz de automatizar a análise de documentos corporativos do setor de Recursos Humanos.

A solução transforma documentos enviados por e-mail em relatórios executivos estruturados automaticamente, utilizando modelos de linguagem (LLMs) e automação no-code.

Projeto desenvolvido como resposta ao desafio acadêmico:

> **Seu Primeiro Copiloto de IA: Criando uma Solução Inteligente com IA Generativa**

---

## 🎯 Problema

O RH enfrenta desafios relacionados a:

- Alto volume de documentos estratégicos
- Análises manuais repetitivas
- Falta de padronização na comunicação executiva
- Tempo elevado para geração de relatórios

*Exemplo do problema: volume de documentos*

[RH Documento.pdf](https://github.com/user-attachments/files/25827731/RH.Documento.pdf)


---

## 💡 Solução Proposta

Criação de um workflow automatizado que:

1. Recebe documentos por e-mail
2. Analisa conteúdo com IA generativa
3. Produz relatório estratégico estruturado
4. Envia automaticamente o resultado

### Fluxo da solução

<img width="1918" height="967" alt="Automação funcionando" src="https://github.com/user-attachments/assets/6ab1b2c3-f5cf-49e3-967a-4315513eae60" />

#### Sequencia de ações da automação com a configuração de cada modolo: 

**1- Gmail (Watch emails ou "Verificar e-mail")**

<img width="753" height="858" alt="Verificar e-mail" src="https://github.com/user-attachments/assets/b453ea4f-2f5a-4e0d-8330-192f95dbde32" />

**2- Gmail (List email attachments media ou "Listar anexos de e-mail (mídia)")**

<img width="722" height="799" alt="Listar anexos de e-mail (mídia)" src="https://github.com/user-attachments/assets/45de45ca-1305-4d58-bd2e-97803abd72d2" />

**3- Google Gemini AI (Upload a file ou "Carregar um arquivo")**

<img width="690" height="763" alt="Carregar um arquivo" src="https://github.com/user-attachments/assets/1f401e5a-0c1b-4d1b-af76-893afd54f32e" />

**4- Google Gemini AI (Creat a response ou "Crie uma resposta")**

<img width="808" height="899" alt="Crie uma resposta 1" src="https://github.com/user-attachments/assets/cfbc4e1a-43e4-444c-b8c7-2b7c1f7102e2" />

**4.1- Onde incluir o pronpt em Google Gemini AI (Creat a response ou "Crie uma resposta")**

<img width="706" height="920" alt="Crie uma resposta 2" src="https://github.com/user-attachments/assets/b7e866a8-ef23-4ca5-85c2-1a012161808f" />

**5- Google Docs (Creat a Document ou "Crie um documento")**

<img width="630" height="702" alt="Crie um documento" src="https://github.com/user-attachments/assets/93c95891-b5b2-44b0-9a4e-97637677055d" />

**6- Gmail (Send an email ou "Envie um e-mail")**

<img width="659" height="914" alt="Envie um e-mail" src="https://github.com/user-attachments/assets/35a15a4b-a258-4224-9b94-8de303321617" />

**6.1- Gmail (Send an email ou "Envie um e-mail")**

<img width="668" height="928" alt="Envie um e-mail 2" src="https://github.com/user-attachments/assets/f3bcac3d-72c6-4406-873d-6d01215ed626" />

### Como usar:

- Envie um documento de RH por e-mail para o endereço configurado no sistema.
- O workflow será acionado, analisará o documento, gerará o relatório e enviará o resultado para o gestor automaticamente.

#### Resultado

<img width="1917" height="1075" alt="E-mail com o resultado recebido automáticamente com documento que possui o resumo em anexo" src="https://github.com/user-attachments/assets/61c70c07-7b05-4fa9-8528-09ada8e21b0f" />

##### Documento que vem em anexo no e-mail de resposta da autoção com o resumo: 

[Ata de Reunião – Comitê de Desenvolvimento de Pessoas (1).pdf](https://github.com/user-attachments/files/25828392/Ata.de.Reuniao.Comite.de.Desenvolvimento.de.Pessoas.1.pdf)



---

## 🧠 Conceitos de IA Aplicados

- IA Generativa (LLMs)
- Prompt Engineering
- Processamento de Linguagem Natural (NLP)
- Automação no-code

---

## ⚙️ Arquitetura do Sistema

Workflow implementado no **Make.com**: https://us2.make.com/public/shared-scenario/XN8LCUtoeha/analise-de-documento-rh
