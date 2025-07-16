# 🏨 Sistema de Reservas de Hotel em Java

Este projeto implementa um sistema desktop de gerenciamento de hotel utilizando Java. Ele permite realizar o cadastro de clientes, quartos e reservas, além de listar dados e gerar relatórios em PDF.

<img width="548" height="229" alt="Captura de tela 2025-07-15 183155" src="https://github.com/user-attachments/assets/eb23de72-0f62-4daf-9850-21dc3ad3b130" />
<img width="774" height="417" alt="Captura de tela 2025-07-15 183211" src="https://github.com/user-attachments/assets/ecb7888d-6d5c-4831-bf74-8ef9e4e94521" />
<img width="500" height="240" alt="Captura de tela 2025-07-15 183218" src="https://github.com/user-attachments/assets/56ff6986-ec86-4238-84f3-c2c35310ad33" />
<img width="721" height="408" alt="Captura de tela 2025-07-15 183228" src="https://github.com/user-attachments/assets/e879e890-50e8-49b9-92f9-92186ecdb6d3" />
<img width="735" height="378" alt="Captura de tela 2025-07-15 183258" src="https://github.com/user-attachments/assets/f211ec0c-8b71-4e69-ae6e-ba6eb1e06362" />
<img width="446" height="295" alt="Captura de tela 2025-07-15 183308" src="https://github.com/user-attachments/assets/f2e4777b-9076-48d6-a5f1-5f0188ca2fb9" />
<img width="493" height="193" alt="Captura de tela 2025-07-15 183348" src="https://github.com/user-attachments/assets/8f8c053c-1cb0-415d-98cb-8d5ce2d857d1" />
<img width="655" height="204" alt="Captura de tela 2025-07-15 183150" src="https://github.com/user-attachments/assets/3247bdcf-ae8a-4b97-a5ff-3c9ed1bef6c8" />

---

## 🔧 Requisitos

- Java JDK 11 ou superior  
- MySQL Server  
- NetBeans 12+ ou outro IDE com suporte a Swing  
- Biblioteca externa: `OpenPDF` (para geração de relatórios em PDF)

---

## ▶️ Como Executar

1. Clone este repositório ou importe no NetBeans
2. Crie o banco de dados MySQL com nome `hotel_reservas`
3. Execute o script de criação das tabelas (em `/sql`)
4. Configure a conexão com o banco nas classes `Repositorio*`
5. Execute a classe `SistemaHotel.java` ou abra o formulário `TelaLogin`

---

## ✅ Funcionalidades

- Login com autenticação de usuário
- Cadastro de clientes, quartos e reservas
- Interface gráfica com Swing (JFrame, JTable, etc.)
- Relacionamento entre reservas, clientes e quartos
- Listagem com JTable em cada módulo
- Geração de relatório completo em **PDF**


---

## 📄 relatorio.txt (Relatório Explicativo)

### 1. CENÁRIO ESCOLHIDO
O sistema simula um hotel com múltiplos clientes e quartos. A aplicação controla reservas de forma integrada.

### 2. DESCRIÇÃO FUNCIONAL
O sistema possui uma interface gráfica com as seguintes funcionalidades:

- Login de acesso
- Menu principal com opções de cadastro e relatórios
- Cadastro e listagem de:
  - Clientes (nome, CPF)
  - Quartos (número, tipo, preço)
  - Reservas (cliente, quarto, data de entrada e saída)
- Geração de relatório em PDF com todos os dados cadastrados

 
<img width="504" height="517" alt="Captura de tela 2025-07-15 212837" src="https://github.com/user-attachments/assets/13fce02e-68c5-4884-b431-bc8420c97d35" />


### 3. JUSTIFICATIVA DAS ESCOLHAS

- O banco de dados MySQL permite persistência real dos dados.
- O padrão MVC foi utilizado para organizar a estrutura do código.
- O relatório em PDF oferece praticidade para impressão e arquivamento.

---

Este sistema tem fins didáticos e serve como base para projetos com CRUD, banco de dados, interface gráfica e relatórios.
