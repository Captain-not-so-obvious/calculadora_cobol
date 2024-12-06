# Calculadora em COBOL

### Descrição
Este projeto implementa uma **calculadora simples** em COBOL que permite realizar as operações básicas: soma, subtração, multiplicação e divisão. Ele foi projetado para demonstrar o uso de divisões, variáveis e lógica condicional em COBOL.

---

### Recursos Implementados
1. **Interatividade:**
   - Usuário pode selecionar a operação desejada.
   - Aceita dois números como entrada.

2. **Operações Disponíveis:**
   - Soma
   - Subtração
   - Multiplicação
   - Divisão

3. **Controle de Fluxo:**
   - Usuário pode continuar realizando cálculos ou encerrar o programa.

4. **Tratamento de Opções Inválidas:**
   - Exibição de mensagem quando uma opção inválida é escolhida.

---

### Estrutura do Código

1. **Divisão de Identificação:**
   - Define o nome do programa e propósitos básicos.

2. **Divisão de Dados:**
   - Declara variáveis usadas para armazenar os números e o resultado.

3. **Divisão de Procedimentos:**
   - Inclui a lógica principal e procedimentos para cada operação:
     - `PROC-SOMAR`
     - `PROC-SUBTRAIR`
     - `PROC-DIVIDIR`
     - `PROC-MULTIPLICAR`
     - `PROC-ENCERRAR`

---

### Como Usar
1. **Compilação:**
   Compile o programa usando o compilador COBOL, como `cobc`:
   ```bash
   cobc -x -o calculadora calculadora.cob
   ```

2. **Execução:**
   Execute o programa compilado:
   ```bash
   ./calculadora
   ```

3. **Interação:**
   - Escolha o tipo de operação no menu exibido.
   - Insira os dois números.
   - Veja o resultado da operação.
   - Escolha se deseja realizar outra operação ou encerrar.

---

### Exemplo de Uso
1. **Menu Inicial:**
   ```
   ********************************************
   Selecione o modo que deseja:
   <1> para somar
   <2> para subtrair
   <3> para dividir
   <4> para multiplicar
   *********************************************
   ```

2. **Entradas do Usuário:**
   - Escolha `<1>` para somar.
   - Insira o primeiro número: `5`
   - Insira o segundo número: `3`

3. **Saída:**
   ```
   A soma de 5 + 3 é 8
   ```

---

### Personalização
- Alterações no design ou funcionalidade podem ser feitas nas seções:
  - **WORKING-STORAGE SECTION:** Para definir novos dados.
  - **PROCEDURE DIVISION:** Para adicionar novas operações ou mensagens.

---

### Autor
**Fillipe Moreira**  
Data: 10/02/2024  
