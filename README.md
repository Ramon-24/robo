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
````

## 📸 Demonstração
<div align="center"> <img src="demo_gestures.gif" width="600" alt="Demonstração dos gestos"/> </div>


## Como Executar
```
git clone https://github.com/Ramon-24/GestureControl
cd GestureControl

python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate  # Windows

pip install -r requirements.txt
python main.py
````

## 🎮 GameHub
<p align="center"> <strong>Plataforma de gamificação educacional</strong> </p><div align="center"> <img src="https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow?style=for-the-badge"/> <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js"/> <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase"/> </div>



# 📱 ContadorFlutter

<p align="center">
  <strong>Aplicativo mobile para contagem e sorteio</strong>
</p>

<div align="center">
  <img src="https://img.shields.io/badge/Status-Live-success?style=for-the-badge&logo=google-play"/>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter"/>
  <img src="https://img.shields.io/badge/Downloads-500+-blue?style=for-the-badge"/>
</div>

---

## 📌 Recursos Principais

- Contador configurável com histórico
- Sistema de sorteio com animações
- Exportação de resultados em CSV
- Modo escuro e acessibilidade

**Estatísticas:**
- 4.8/5 na Play Store
- 92% de retenção após 30 dias

---

## 📲 Telas do App

<div align="center">
  <img src="screenshots/counter.png" width="30%" alt="Contador"/>
  <img src="screenshots/draw.png" width="30%" alt="Sorteio"/> 
  <img src="screenshots/history.png" width="30%" alt="Histórico"/>
</div>

---

## 📊 Dados Técnicos

```mermaid
pie
    title Arquitetura
    "UI Flutter" : 45
    "Lógica Dart" : 35
    "Integrações" : 20
