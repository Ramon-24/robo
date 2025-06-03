# 🤖 GestureControl

<p align="center">
  <strong>Controle por reconhecimento de gestos com Python</strong>
</p>

<div align="center">
  <img src="https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge&logo=check-circle"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv"/>
  <img src="https://img.shields.io/badge/Precisão-85%25-brightgreen?style=for-the-badge"/>
</div>

---

## 🧾 Sobre o Projeto

Sistema de controle por gestos desenvolvido para automação residencial, capaz de:

- Reconhecer 8 gestos diferentes com 85% de precisão
- Controlar funções do sistema operacional
- Modularidade para adição de novos comandos

**Diferenciais:**
- Baixo consumo de recursos (rodando em Raspberry Pi)
- Configuração personalizável via JSON

---

## 🛠️ Arquitetura do Sistema

```mermaid
graph TD
    A[Webcam] --> B[OpenCV]
    B --> C[Processamento de Imagem]
    C --> D[Classificação de Gestos]
    D --> E[Execução de Comandos]
    E --> F[Sistema Operacional]
