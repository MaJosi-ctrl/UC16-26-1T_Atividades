# Atividade Prática — Avaliação de UX/UI

## 1ª Heurística de Nielsen: Visibilidade do Status do Sistema

**Objetivo:** Navegar por um e-commerce fictício, simulando uma experiência completa de compra. Durante a navegação, vocês deverão identificar problemas relacionados à visibilidade do status do sistema.

---

## 1. Cadastro e Login

- [x] Criar uma nova conta.
- [x] Tentar cadastrar uma conta com dados inválidos.
- [x] Fazer login com os dados corretos.
- [x] Tentar fazer login com senha incorreta.
- [ ] Sair da conta e entrar novamente.

## 2. Navegação e Pesquisa

- [x] Pesquisar um produto pelo nome.
- [x] Pesquisar um produto que não existe.
- [x] Aplicar filtros no catálogo.
- [x] Alterar a ordenação dos produtos.
- [x] Navegar entre diferentes produtos.

## 3. Produtos e Favoritos

- [x] Abrir os detalhes de um produto.
- [x] Adicionar um produto aos favoritos.
- [x] Remover um produto dos favoritos.
- [x] Adicionar diferentes produtos ao carrinho.
- [x] Adicionar o mesmo produto mais de uma vez.

## 4. Carrinho de Compras

- [x] Abrir o carrinho.
- [x] Aumentar a quantidade de um produto.
- [x] Diminuir a quantidade de um produto.
- [x] Remover um produto do carrinho.
- [x] Conferir o valor total da compra.

## 5. Finalização da Compra

- [x] Iniciar o processo de checkout.
- [x] Preencher os dados de entrega.
- [x] Tentar continuar com campos incompletos.
- [x] Selecionar uma forma de pagamento.
- [x] Finalizar a compra simulada.
- [x] Verificar se existe confirmação do pedido.

## 6. Conta e Pedidos

- [x] Consultar os dados da conta.
- [x] Procurar o histórico de pedidos.
- [x] Verificar as informações de uma compra.
- [x] Tentar identificar o status do pedido.

---

## 7. O que observar durante os testes?

Durante cada ação, respondam às seguintes perguntas:

1. O sistema informou que recebeu minha ação?
2. Consigo identificar o que está acontecendo?
3. Sei se a operação foi concluída, está em andamento ou apresentou algum erro?
4. O sistema fornece informações suficientes para que eu saiba o que fazer em seguida?

---

## 8. Entrega da Atividade

Cada aluno ou grupo deverá identificar **pelo menos 8 problemas de usabilidade** relacionados à primeira heurística de Nielsen.

Para cada problema encontrado, registre:

| Item | Descrição |
|---|---|
| **Tela ou funcionalidade** | Onde o problema aconteceu? |
| **Ação realizada** | O que vocês estavam tentando fazer? |
| **Problema identificado** | Qual informação o sistema deixou de apresentar? |
| **Solução proposta** | Como a interface poderia ser melhorada? |

### Modelo de Registro dos Problemas

| Nº | Tela/Funcionalidade | Ação realizada | Problema identificado | Solução proposta |
|---|---|---|---|---|
| 1 | **Cadastro** | Criar uma nova conta preenchendo todos os campos corretamente. | Após clicar em criar conta, o sistema não apresenta nenhuma confirmação de que o cadastro foi concluído. | Exibir uma mensagem de sucesso, como "Cadastro realizado com sucesso!". |
| 2 | Cadastro | Tentar cadastrar uma conta utilizando senhas diferentes na confirmação. | O sistema não informa por que o cadastro não foi realizado. | Exibir uma mensagem explicando que as senhas não coincidem. |
| 3 | Login | Tentar entrar utilizando um e-mail cadastrado e uma senha incorreta. | O sistema não apresenta nenhuma mensagem informando que as credenciais estão incorretas. | Exibir uma mensagem de erro informando que o e-mail ou a senha estão incorretos. |
| 4 | Favoritos | Clicar no ícone de coração para adicionar um produto aos favoritos. | O ícone não muda de aparência e o sistema não informa se o produto foi adicionado. | Alterar a aparência do coração e apresentar uma mensagem confirmando a adição aos favoritos. |
| 5 | Carrinho de compras | Adicionar um produto ao carrinho. | Após clicar em "Adicionar ao carrinho", não aparece nenhuma confirmação e o contador do carrinho não é atualizado. | Atualizar o contador do carrinho e exibir uma mensagem confirmando que o produto foi adicionado. |
| 6 | Carrinho de compras | Aumentar ou diminuir a quantidade de um produto. | A quantidade e o valor total não são atualizados imediatamente na tela. | Atualizar automaticamente a quantidade, o subtotal e o valor total após cada alteração. |
| 7 | Finalização da compra | Clicar em "Confirmar pedido" para finalizar a compra. | Não aparece nenhuma confirmação de conclusão. O usuário permanece na tela de pagamento sem saber se a operação foi realizada. | Exibir uma tela de confirmação com o número do pedido, o valor total e uma mensagem de sucesso. |
| 8 | Pagamento | Selecionar PIX como forma de pagamento. | A interface apenas oculta os campos do cartão, sem apresentar informações sobre como o pagamento por PIX funcionará. | Exibir as instruções e o status da opção de pagamento selecionada. |

---

## 9. Orientações Importantes

**Atenção:** Não basta escrever que determinada funcionalidade não funcionou. É necessário explicar qual informação está faltando e como o sistema deveria comunicar seu estado ao usuário.

### Desafio Final

O site possui problemas intencionais de usabilidade. Vocês deverão descobri-los sem receber dicas sobre onde estão.

O objetivo não é apenas identificar falhas, mas também **propor soluções que tornem a experiência do usuário mais clara, intuitiva e confiável.**
