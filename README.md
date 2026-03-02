# 🏥 Sistema de Gerenciamento de Clínica Médica

Este é um projeto acadêmico desenvolvido para consolidar os fundamentos de **Programação Orientada a Objetos (POO)** em Java.

## 🚀 Funcionalidades
- Cadastro de Médicos e Pacientes.
- Agendamento de Consultas com validação de data.
- Gestão de Exames com prazos mínimos.
- Registro de comparecimento e histórico clínico vinculado.

## 🛠️ Regras de Negócio Implementadas
1. **Encapsulamento:** Todos os atributos são `private` com acesso via construtores e métodos.
2. **Validação de Data:** Consultas só podem ser agendadas para o futuro.
3. **Fluxo de Atendimento:** O histórico clínico só pode ser gerado se o paciente tiver comparecido à consulta.
4. **Integridade de Dados:** Prazos de exames devem ser positivos e históricos não podem ser vazios.
