# Casos de Teste – Login

## Técnica aplicada:
- Particionamento de Equivalência

---

### CT01 – Login com dados válidos
Passos:
1. Inserir usuário válido
2. Inserir senha válida
3. Clicar em Login

Resultado Esperado:
Usuário deve acessar a página de produtos.

---

### CT02 – Senha inválida
Passos:
1. Inserir usuário válido
2. Inserir senha incorreta
3. Clicar em Login

Resultado Esperado:
Sistema deve exibir mensagem de erro.

---

### CT03 – Campos vazios
Passos:
1. Não preencher campos
2. Clicar em Login

Resultado Esperado:
Sistema deve exibir mensagem solicitando preenchimento.
