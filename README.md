# 🍷 Sistema de Monitoramento Ambiental para Vinheria

## 👥 Integrantes

| Nome | RM |
|-------|----|
| Matheus Mendes | RM569559 |
| Matheus Sato | RM569392 |

---

## 📌 Sobre o Projeto

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
[Cole aqui o link da simulação](https://wokwi.com/projects/463747130938169345)

**GitHub:**  
[Cole aqui o link do repositório](https://github.com/MatheusSato00/O-Caso-Da-Vinheria-Angelo-/edit/main)

**Vídeo Demonstrativo:**  
[Cole aqui o link do vídeo](https://teams.microsoft.com/l/message/19:df1ff602-85f1-485e-bee0-d043ce08b2dc_e4ce7cad-0953-4030-ab62-66c6edacd7b8@unq.gbl.spaces/1778548715455?context=%7B%22contextType%22%3A%22chat%22%7D)

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

