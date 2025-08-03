# 🚛 Gerador de PDFs para Assinatura de Motoristas - Integração TOTVS RM

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-150458?logo=pandas)
![Oracle](https://img.shields.io/badge/Oracle-Database-F80000?logo=oracle)
![Selenium](https://img.shields.io/badge/Selenium-Web%20Automation-43B02A?logo=selenium)
![PDF Automation](https://img.shields.io/badge/PDF-Automation-lightgrey)

---

## 💡 Sobre o Projeto

Este projeto foi desenvolvido para **automatizar a geração de documentos de assinatura para motoristas**, com dados extraídos diretamente do **TOTVS RM (banco Oracle)**.

O sistema realiza a consulta de informações no RM, separa automaticamente os motoristas com **mais de 5 anos de empresa** e **menos de 5 anos**, organiza os dados utilizando **Pandas**, e gera **arquivos PDF prontos para impressão e assinatura**, otimizando um processo que antes era 100% manual.

Além disso, a ferramenta automatiza etapas no navegador utilizando **Selenium**, como download de informações complementares ou verificação de dados no portal da empresa.

---

## ✨ Funcionalidades

- 🗄️ **Integração com TOTVS RM (Oracle DB)**
- 🐼 **Processamento e Organização de Dados com Pandas**
- 📄 **Geração Automática de PDFs para Assinatura**
- 📊 **Separação Inteligente de Motoristas (+5 anos e -5 anos de casa)**
- 🌐 **Automação Web com Selenium (extração de documentos complementares)**
- 📁 **Organização de arquivos em pastas automáticas**
- ✔️ **Execução rápida via script Python, sem intervenção manual**

---

## 🛠️ Tecnologias Utilizadas

| Área | Tecnologias |
|------|-------------|
| **Linguagem Principal** | Python 3.10+ |
| **Banco de Dados** | Oracle (TOTVS RM via cx_Oracle) |
| **Manipulação de Dados** | Pandas |
| **Automação Web** | Selenium |
| **Geração de PDFs** | ReportLab / FPDF |
| **Organização de Arquivos** | Python OS / Pathlib |

---

## 🚀 Impacto e Resultados

- 🕒 **Redução de tempo de execução de horas para minutos**
- ❌ **Eliminação de processos manuais e retrabalho**
- 📁 **Arquivos organizados automaticamente em pastas por categoria (+5 anos / -5 anos)**
- 📊 **Facilitou o controle do setor administrativo em processos de auditoria**
- 🔄 **Processo replicável para outras categorias de colaboradores**

---

## 📂 Estrutura dos Arquivos Gerados

---

## ⚙️ Como Funciona

1. O script se conecta ao **TOTVS RM (Oracle)** e extrai as informações dos motoristas.
2. Utilizando **Pandas**, os dados são tratados e separados entre motoristas com mais ou menos de 5 anos de empresa.
3. Para documentos complementares, o **Selenium** automatiza o acesso ao portal da empresa, baixando ou verificando arquivos.
4. Os PDFs são gerados automaticamente, já formatados para assinatura.
5. Os arquivos são organizados em pastas específicas, prontos para impressão e entrega.

---

## 📬 Contato

Desenvolvido por **Raquel Daud**  
🔗 [LinkedIn](https://www.linkedin.com/in/raquel-daud-72a3991a2/) | 📧daudpython@gmail.com

---



