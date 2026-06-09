# 🧠 ASTRASYNC AI

### Sistema Inteligente de Monitoramento Humano

---

## 🚀 Visão Geral

O **ASTRASYNC AI** é uma solução embarcada que simula o monitoramento contínuo de condições fisiológicas e cognitivas humanas, utilizando um sistema baseado em Arduino.

A proposta integra leitura de variáveis críticas, análise de risco em tempo real e feedback visual/auditivo, criando uma experiência semelhante a interfaces biomédicas futuristas.

---

## 🎯 Objetivo

Desenvolver um sistema capaz de:

* Monitorar variáveis simuladas do estado humano
* Identificar padrões de risco
* Classificar níveis de alerta automaticamente
* Fornecer feedback visual e sonoro em tempo real

---

## 🧩 Arquitetura da Solução

### 🔹 Entrada de Dados

Sensores simulados por potenciômetros:

* Estresse (%)
* Fadiga (%)
* Sono (horas)
* Frequência cardíaca (BPM)

### 🔹 Processamento

O sistema aplica uma lógica de análise baseada em:

* Cálculo de estabilidade
* Simulação de tempo de reação (dinâmico)
* Classificação de risco em 3 níveis

### 🔹 Saída

* Display LCD (dados em tempo real)
* LEDs de status (verde, amarelo, vermelho)
* Buzzer (alerta crítico)
* Monitor Serial (debug completo)

---

## 🧠 Lógica Inteligente

O sistema utiliza uma abordagem baseada em regras:

* **CRÍTICO**

  * Estresse ≥ 70%
  * Fadiga ≥ 70%
  * Sono ≤ 3h
  * Tempo de reação elevado

* **ATENÇÃO**

  * Valores intermediários de risco

* **NORMAL**

  * Condições estáveis

Além disso, o **tempo de reação é gerado dinamicamente**, sendo influenciado por estresse e fadiga, simulando comportamento humano realista.

---

## 🛠️ Tecnologias e Componentes

### Hardware

* Arduino UNO
* LCD I2C 16x2
* 4 Potenciômetros
* LEDs (Verde, Amarelo, Vermelho)
* Buzzer
* Protoboard + Jumpers

### Software

* Linguagem C++ (Arduino)
* Biblioteca `LiquidCrystal_I2C`
* Simulação via Tinkercad

---

## 🔌 Diagrama do Sistema

O circuito é composto por:

* Entradas analógicas (A0–A3) para leitura dos sensores
* Comunicação I2C (A4/A5) para o display
* Saídas digitais para LEDs e buzzer

---

## ▶️ Execução

1. Monte o circuito conforme o projeto
2. Faça upload do código no Arduino
3. Abra o Monitor Serial (9600 baud)
4. Ajuste os potenciômetros
5. Observe:

   * Dados no LCD
   * Mudança de LEDs
   * Ativação do buzzer em risco crítico

---

## 📊 Monitoramento em Tempo Real

O sistema exibe:

* Valores individuais dos sensores
* Tempo de reação (ms)
* Estabilidade geral
* Status do sistema

---

## 🎥 Video

[Assista ao vídeo da solução](https://youtu.be/Oq9U5mu1O7g?si=Ou5aUEKzyRdNNOh0)

---

## 🌐 Simulação

🔗 https://www.tinkercad.com/things/bFlCcQYFHWs-astrasync-ai-gs-edge

---

## 💻 Código Fonte

Todo o código está disponível neste repositório, incluindo:

* Leitura de sensores
* Processamento lógico
* Interface com LCD
* Sistema de alertas

---

## 👥 Equipe

* Matheus Medeiros Da Cunha RM 572780
* Arthur Caram Fiorese RM 569578
* Gustavo Ferreira Silva RM 571675
* Felipe Ricardo Moreira Aguiar RM 573410
* Matheus Sequeira Franco RM 571127


---

## 🧬 Diferenciais do Projeto

* Simulação de comportamento humano (tempo de reação dinâmico)
* Interface visual inspirada em sistemas biomédicos
* Feedback em múltiplos níveis (visual + sonoro)
* Estrutura modular e escalável

---

## 🔮 Possíveis Evoluções

* Integração com sensores reais (batimento, temperatura, etc.)
* Conexão com aplicativo mobile
* Uso de IA para análise preditiva
* Dashboard web em tempo real

---

## 📌 Conclusão

O ASTRASYNC AI demonstra como sistemas embarcados podem ser utilizados para simular e analisar condições humanas complexas, servindo como base para aplicações reais em saúde, segurança e monitoramento inteligente.

---
