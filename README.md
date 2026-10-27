# Pharos Read Contract State Agent[cite: 10]

Um agente desenvolvido em **Java** para a Pharos Agent Arena concebido para ler o estado de um contrato inteligente em tempo real através do Chain MCP e apresentá-lo de forma compreensível para humanos[cite: 10].

## 📋 Requisitos Cumpridos[cite: 10]

1. **Leitura Multivalor (Req. 01):** Lê pelo menos 3 valores diferentes do contrato (`name`, `totalSupply` e `owner`) via Chain MCP[cite: 10].
2. **Metadados de Bloco (Req. 02):** Apresenta o endereço exato do contrato e o número do bloco em que os dados foram obtidos[cite: 10].
3. **Formatação Humana (Req. 03):** Converte valores brutos aplicando decimais de tokens e rotula corretamente os endereços[cite: 10].
4. **Documentação README (Req. 04):** Inclui detalhes sobre o contrato escolhido, instruções de execução e exemplo de saída[cite: 10].

## 📄 Detalhes do Contrato Escolhido
- **Contrato:** Pharos Staked Token (`0x71C...3829`)[cite: 10]
- **Rede:** Pharos Atlantic Testnet[cite: 10]

## 🚀 Como Executar

1. Certifique-se de ter o **Java JDK** instalado.
2. Compile o ficheiro:
   ```bash
   javac ReadContractState.java
