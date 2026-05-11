# 🍷 Sistema de Monitoramento Ambiental para Vinheria

Projeto desenvolvido para o **Checkpoint 02 – Edge Computing & Computer Systems (FIAP)**, com foco no monitoramento das condições ambientais de uma vinheria.

O sistema realiza o monitoramento de **luminosidade, temperatura e umidade**, exibindo informações em um **LCD 16x2** e emitindo alertas visuais e sonoros quando os valores estão fora da faixa ideal.

---

## 🚀 Funcionalidades

- Monitoramento de **luminosidade**
- Monitoramento de **temperatura**
- Monitoramento de **umidade**
- Exibição de dados no **LCD**
- Alertas com **LEDs**
- **Buzzer** para situações críticas
- Média de **5 leituras dos sensores**

---

## 🛠️ Tecnologias Utilizadas

- **Arduino Uno**
- **C++ (Arduino IDE)**
- **Wokwi**
- **LCD I2C 16x2**
- **DHT22**
- **LDR**
- **LEDs**
- **Buzzer**
- **Protoboard**

---

## ⚙️ Regras do Sistema

### 🌡️ Temperatura
- **10°C a 15°C** → Ideal  
- **Acima de 15°C** → Temperatura alta  
- **Abaixo de 10°C** → Temperatura baixa  

### 💧 Umidade
- **50% a 70%** → Ideal  
- **Fora da faixa** → Alerta  

### 💡 Luminosidade
- **Baixa** → LED verde  
- **Média** → LED amarelo  
- **Alta** → LED vermelho + buzzer  

---

## 🔗 Links do Projeto

**Wokwi:**  
(https://wokwi.com/projects/463747130938169345)

**GitHub:**  
(https://github.com/MatheusSato00/O-Caso-Da-Vinheria-Angelo-)

**Vídeo Demonstrativo:**  
Cole aqui o link do vídeo

---

## 📂 Estrutura do Projeto

```bash
📁 projeto
│── sketch.ino
│── diagram.json
│── README.md
```

---

## 📄 Conclusão

Este projeto aplica conceitos de **IoT, sensores e automação**, simulando um sistema de monitoramento ambiental para auxiliar na preservação adequada de vinhos.

