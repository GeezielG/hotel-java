# 🏨 Sistema de Reservas de Quartos (Java)

Este é um pequeno projeto em Java que simula um sistema de reservas de quartos de hotel, com foco em manipulação de datas e tratamento de exceções.

## 📋 Funcionalidades

- Registrar uma nova reserva informando número do quarto, data de check-in e check-out.
- Verificar se a data de check-out é posterior à data de check-in.
- Atualizar as datas da reserva.
- Validar se as novas datas são futuras e se a data de check-out é posterior à de check-in.
- Cálculo automático do número de noites da estadia.

## 📁 Estrutura dos Arquivos

- `Program.java`: Classe principal que interage com o usuário via terminal.
- `Reservation.java`: Classe que representa uma reserva e contém toda a lógica de validação e cálculo da duração.

## 🚀 Como Executar

1. Compile os arquivos:

```bash
javac Program.java Reservation.java
