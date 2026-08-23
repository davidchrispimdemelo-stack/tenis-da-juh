# Tênis da Juh

## 🎉 Bem-vindo!

Site oficial da **Tênis da Juh** — modelos de 1ª e 2ª linha com pedidos pelo WhatsApp.

---

## 📁 Estrutura dos Arquivos

```
tenis-da-juh/
├── index.html              # 🏠 Página principal do site
├── painel.html             # 🎛️  Painel de gerenciamento de produtos
├── produtos.js             # 📦 Catálogo de tênis (dados)
├── logo-tenis-da-juh.png   # 🎨 Logo da marca
└── README.md               # 📄 Este arquivo
```

---

## 🚀 Como Usar

### 1. **Abrir o Site**
   - Abra `index.html` no navegador para acessar o site da loja.

### 2. **Gerenciar Produtos**
   - Abra `painel.html` para adicionar, editar ou remover tênis.
   - Você pode fazer alterações **sem mexer no código**.
   - Quando terminar, clique em "Baixar catálogo atualizado" e substitua o arquivo `produtos.js`.

### 3. **Configurar WhatsApp**
   - No arquivo `index.html`, procure por:
     ```javascript
     const WHATSAPP_NUMBER = "5511999999999";
     ```
   - Substitua `"5511999999999"` pelo seu número do WhatsApp (com código do país).
   - Salve o arquivo.

---

## 💾 Arquivos Importantes

### `index.html`
- A página principal do site
- Contém todo o HTML, CSS e lógica de funcionamento
- **Ajuste o número do WhatsApp aqui!**

### `painel.html`
- Painel administrativo para gerenciar produtos
- Permite adicionar, editar e deletar tênis de forma visual
- Funciona **100% no navegador** — não precisa de internet nem servidor

### `produtos.js`
- Arquivo com a lista de todos os tênis e seus dados
- É atualizado automaticamente quando você usa o painel
- **Não edite manualmente** — use o painel!

### `logo-tenis-da-juh.png`
- Logo da marca em formato PNG
- Usada no header e na seção hero do site

---

## ✨ Funcionalidades

✅ **Carrinho de compras** — Adicione tênis, selecione tamanhos e quantidade  
✅ **Filtros** — Filtre por 1ª linha, 2ª linha ou todos  
✅ **Integração WhatsApp** — Envie o pedido pronto via WhatsApp  
✅ **Painel admin** — Gerenciar produtos sem código  
✅ **Design responsivo** — Funciona em desktop, tablet e celular  
✅ **Sem servidor necessário** — Funciona localmente no navegador  

---

## 📱 Modo de Funcionamento

1. Cliente entra no site e navega pelo catálogo
2. Seleciona tênis, escolhe tamanho e adiciona ao carrinho
3. Clica em "Finalizar pelo WhatsApp 💬"
4. Uma mensagem pré-formatada é enviada para seu WhatsApp
5. Você confirma disponibilidade e combina pagamento/entrega

---

## 🔧 Personalização

### Cores
As cores principais estão definidas no início do CSS em `index.html` e `painel.html`:

```css
:root {
  --rosa: #ef8ea0;
  --marrom: #3b2824;
  --dourado: #c7983f;
  /* ... */
}
```

### Texto
Altre qualquer texto nos arquivos HTML usando um editor de texto.

---

## 🆘 Dúvidas?

- **O painel não carrega os produtos?** → Certifique-se que `produtos.js` está no mesmo local que `painel.html`
- **WhatsApp não abre?** → Verifique se o número está correto e no formato internacional (5511999999999)
- **Imagens dos tênis não aparecem?** → Use o painel para fazer upload das fotos

---

**Desenvolvido com 💕 para Tênis da Juh**
