# 🚦 Sistema de Controle de Semáforos Inteligentes

## 📋 Descrição

Este projeto implementa um **Sistema de Controle de Semáforos Inteligentes** utilizando a linguagem **C#** e o **.NET**.  
O sistema é capaz de:

- Monitorar o funcionamento de diversos semáforos.
- Detectar e registrar falhas automaticamente.
- Gerar alertas em tempo real.
- Emitir relatórios do status atual.

---

## 🛠️ Tecnologias Utilizadas

- C#
- .NET Core / .NET 6+  
- Visual Studio Code (VS Code)

---

## 🧱 Estrutura do Sistema

- **Classe `Semaforo`**: Representa cada semáforo, com status de energia e operacional.
- **Classe `Falha`**: Registra cada falha detectada.
- **Classe `SistemaControleSemaforos`**: Gerencia o sistema, realizando monitoramento, registro de falhas e geração de relatórios.
- **Classe `Program`**: Executa a simulação e demonstra as funcionalidades.

---

## ▶️ Como Executar

### ✅ Pré-requisitos:

- [.NET SDK](https://dotnet.microsoft.com/en-us/download) instalado.

### ✅ Passos:

1. Clone ou baixe este repositório.
2. Abra o terminal e crie um novo projeto:

```bash
dotnet new console -o SistemaSemaforos
cd SistemaSemaforos
# global-cs
