# dio-ransomware-python-simulation
Implementação didática de mecanismos de criptografia e descriptografia simétrica de ficheiros em Python (AES/CTR) para o desafio prático de cibersegurança da DIO.

# Simulação Didática de Ransomware com Python

Projeto desenvolvido como parte prática do módulo de segurança ofensiva e defesa da **Formação Cybersecurity Specialist** pela [DIO (Digital Innovation One)](https://www.dio.me/).

## ⚠️ Aviso Legal / Disclaimer
Este código foi desenvolvido com finalidade **estritamente educacional**, com foco em compreensão dos fundamentos de criptografia simétrica, análise de comportamento de ameaças e resposta a incidentes. Não deve ser executado fora de ambientes controlados de laboratório (sandbox/VM).

---

## 💻 Visão Geral do Projeto
O objetivo prático é demonstrar o mecanismo elementar utilizado por ameaças do tipo ransomware para sequestro de ficheiros locais, implementando:
1. **Criptografia simétrica** de um ficheiro-alvo utilizando a cifra AES (*Advanced Encryption Standard*) em modo de operação CTR.
2. **Substituição de extensão** para simular o bloqueio de acesso ao conteúdo original.
3. **Descriptografia e restauração** com recurso à mesma chave secreta para recuperação da integridade do ficheiro.

---

## 🛠️ Tecnologias e Bibliotecas
* **Linguagem:** Python 3.8+
* **Biblioteca de Criptografia:** `pyaes` (ou módulo nativo equivalente)
* **Manipulação de Sistema de Ficheiros:** `os`

---

## 📂 Estrutura do Repositório

```text
├── encrypter.py        # Script responsável pela cifragem e remoção do ficheiro original
├── decrypter.py        # Script responsável pela decifragem e restauro do ficheiro
├── teste.txt           # Ficheiro de texto simples utilizado como cobaia do teste
└── README.md           # Documentação técnica do projeto
