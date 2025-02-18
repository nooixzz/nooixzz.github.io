# 🛠️ Portfólio de QA - Henrique Ferreira Melo
## 📌 Sobre Mim
🎯 *Objetivo:* Iniciar minha carreira como QA Tester, garantindo a qualidade de software através de testes bem documentados.  
📧 *Contato:* henriqueferreiramelo9@gmail.com
🔗 *LinkedIn:* www.linkedin.com/in/henrique-ferreira-432912197


---

## *📂 Casos de Teste*

### *Teste 01 - Login com senha errada*

| ID  | Caso de Teste  | Passos  | Resultado Esperado  | Status (Passou/Falhou) |
|-----|---------------|---------|---------------------|------------------------|
| CT01 | Testar login com senha errada | 1. Acessar o site do Steam  2. Ir para a tela de login  3. Digitar o Nome de Usuário correto e senha incorreta | 4. Clicar em "Entrar" | O site deve exibir uma mensagem de erro "Senha incorreta" | ✅ Passou |

### *Teste 02 - Login sem preencher todos os campos*

| ID  | Caso de Teste  | Passos  | Resultado Esperado  | Status (Passou/Falhou) |
|-----|---------------|---------|---------------------|------------------------|
| CT02 | Testar login incompleto | 1. Acessar a página de login 2. Preencher apenas o Nome de Usuário 3. Tentar avançar para a próxima etapa | O sistema deve exibir um alerta indicando que todos os campos obrigatórios devem ser preenchidos | ❌ Falhou |

### *Teste 03 - Recuperação de Senha*

| ID  | Caso de Teste  | Passos  | Resultado Esperado  | Status (Passou/Falhou) |
|-----|---------------|---------|---------------------|------------------------|
| CT03 | Testar recuperação de senha com e-mail inválido | 1. Acessar a página de login  2. Clicar em "Esqueci minha senha"  3. Inserir um e-mail inválido  4. Clicar em "Enviar" | O sistema deve exibir uma mensagem de erro "E-mail não encontrado" | ✅ Passou |

### *Teste 04 - Adicionar produto ao carrinho*

| ID  | Caso de Teste  | Passos  | Resultado Esperado  | Status (Passou/Falhou) |
|-----|---------------|---------|---------------------|------------------------|
| CT04 | Verificar se um produto pode ser adicionado ao carrinho | 1. Acessar um produto na loja  2. Clicar no botão "Adicionar ao carrinho"  3. Ir até o carrinho de compras | O produto deve aparecer na lista de itens do carrinho | ✅ Passou |

### *Teste 05 - Logout do sistema*

| ID  | Caso de Teste  | Passos  | Resultado Esperado  | Status (Passou/Falhou) |
|-----|---------------|---------|---------------------|------------------------|
| CT05 | Verificar se o logout funciona corretamente | 1. Fazer login na conta  2. Clicar no botão de logout  3. Tentar acessar uma página restrita | O usuário deve ser redirecionado para a página de login | ✅ Passou |

---

## 🛠 Relatórios de Bugs

### ❌ Bug 01 -  Sem nenhuma mensagem de erro genérica no login  
*Passos para Reproduzir:*  
1. Acessar o Steam  
2. Ir para a página de login  
3. Inserir um e-mail válido  
4. Não digitar nenhuma senha  
5. Clicar em "Entrar"  

🔴 *Resultado Atual:* Não acontece nada, nenhuma mensagem de erro
✅ *Resultado Esperado:* O site deve exibir "Preencha todos os espaços" ou, "Insira a sua senha"  
⚠️ *Gravidade:* Média/Baixa  

---

## 📢 Conclusão  
Este portfólio demonstra minha capacidade de identificar e documentar bugs de forma clara. Estou buscando oportunidades como QA Tester para ajudar na melhoria da qualidade de software.  

📩 *Entre em contato comigo para mais informações!*
