# ✅ Casos de Teste - Amazon Brasil

Documentação dos testes realizados durante a navegação pública na Amazon Brasil.

---

## 🧪 CT001 - Pesquisa por produto
- **Título:** Buscar por "notebook dell"
- **Pré-condição:** Acessar o site [amazon.com.br](https://www.amazon.com.br)
- **Passos:**
  1. Digitar "notebook dell" na barra de pesquisa
  2. Clicar no ícone de busca
- **Resultado Esperado:** Lista de produtos relacionados ao termo "notebook dell"
- **Resultado Obtido:** Conforme esperado
- **Status:** ✅ Aprovado

---

## 🧪 CT002 - Verificação de filtros de categoria
- **Título:** Verificar presença e funcionamento de filtros ao buscar por "notebook dell"
- **Pré-condição:** Acessar o site [amazon.com.br](https://www.amazon.com.br)
- **Passos:**
  1. Realizar uma busca por "notebook dell"
  2. Observar os filtros exibidos na lateral esquerda
  3. Aplicar um ou mais filtros como "Tamanho da tela" ou "Marca"
  4. Verificar se os resultados são atualizados conforme o filtro aplicado
- **Resultado Esperado:** Resultados da busca devem refletir os filtros aplicados corretamente
- **Resultado Obtido:** Produtos atualizados conforme os filtros selecionados
- **Status:** ✅ Aprovado

---

## 🧪 CT003 - Adicionar item ao carrinho
- **Título:** Adicionar um produto ao carrinho sem login
- **Pré-condição:** Acesso ao site
- **Passos:**
  1. Buscar por "fone bluetooth"
  2. Selecionar um produto da lista
  3. Clicar em "Adicionar ao carrinho"
- **Resultado Esperado:** Mensagem de confirmação de adição ao carrinho
- **Resultado Obtido:** Ocorreu conforme esperado
- **Status:** ✅ Aprovado

---

## 🧪 CT004 - Teste de link de banner
- **Título:** Verificar redirecionamento de banner principal
- **Pré-condição:** Página inicial da Amazon
- **Passos:**
  1. Clicar em um banner promocional na home
- **Resultado Esperado:** Redirecionar para uma página relacionada à promoção
- **Resultado Obtido:** Página redirecionada corretamente para o conteúdo promocional
- **Status:** ✅ Aprovado

---

## 🧪 CT005 - Teste de responsividade em mobile
- **Título:** Avaliar comportamento e layout da interface em dispositivos móveis
- **Pré-condição:** Utilizar DevTools ou dispositivo móvel real
- **Passos:**
  1. Acessar o site usando a visualização mobile no navegador
  2. Verificar o funcionamento do menu, pesquisa e banners
- **Resultado Esperado:** Elementos bem posicionados e funcionais em tela pequena
- **Resultado Obtido:** Elementos funcionam, mas a fonte apresentada é muito pequena, prejudicando a leitura
- **Status:** ⚠️ Observação crítica de usabilidade
- **Evidência:** ![CT005 - Fonte Mobile](../evidencias-visuais/amazon.png)

---

## 🧪 CT006 - Avaliação de tempo de carregamento
- **Título:** Verificar tempo de carregamento da home
- **Pré-condição:** Acesso com cache limpo e internet estável
- **Passos:**
  1. Abrir DevTools e acessar aba Network
  2. Recarregar a página inicial da Amazon
  3. Verificar tempo total em "Load"
- **Resultado Esperado:** Página totalmente carregada em até 5 segundos
- **Resultado Obtido:** Página carregada completamente em 2,51 segundos
- **Status:** ✅ Aprovado
