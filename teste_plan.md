# Escopo
Sistema de delivery
# Estrategia
Leitura e analise de codigo-fonte
# Recursos
um codigo de um sistema de delivery escrito em html com o nome index.html
localizado no repositorio sistema-delivery no [repositorio](https://github.com/deivisonfassis/sistema_delivery)
# Cronograma
14/10/2026:durante o horario de aula
# Ferramentas utilizadas
vscode e github

---

## Teste Case - CT01
- Objetivo - validar o valor do preco
- Contexto - aplicação rodando de forma local no computador 
- Ação executada - colocar o preço no campo, confirmar pedido
- Saida esperada - o total com a separação decimal com virgula

---

### ISSUE 458 - SEVERIDADE: BAIXA - PRIORIDADE: MEDIA
#### error NaN ao comfirmar o pedido colocando uma letra no campo preco
- **Passos executado**: digitar um letra no campo preco e clicar em confirmar
- **Resultado obtido**: No display foi exibido 'R$ NaN'
- **Resultado esperado**: no display deve ser exibido o total em Reais.