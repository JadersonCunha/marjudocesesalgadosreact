# Marju Confeitaria - Versão React

Este é o site da Marju Confeitaria convertido para React, mantendo todas as funcionalidades e layout originais.

## 🚀 Como executar o projeto

### Pré-requisitos
- Node.js (versão 14 ou superior)
- npm ou yarn

### Instalação e execução

1. **Navegue até a pasta do projeto React:**
   ```bash
   cd "c:\Users\usuario\Desktop\copia marjudoces\marju-react-github"
   ```

2. **Instale as dependências:**
   ```bash
   npm install
   ```

3. **Execute o projeto:**
   ```bash
   npm start
   ```

4. **Acesse no navegador:**
   O projeto será aberto automaticamente em `http://localhost:3000`

## 📁 Estrutura do projeto

```
src/
├── components/          # Componentes React
│   ├── Header.js       # Cabeçalho com navegação
│   ├── Hero.js         # Seção principal
│   ├── ProductsSection.js  # Seção de produtos
│   ├── ContactSection.js   # Formulário de contato
│   ├── Footer.js       # Rodapé
│   ├── AboutModal.js   # Modal sobre a Marju
│   ├── GalleryModal.js # Modal da galeria de produtos
│   ├── CartModal.js    # Modal do carrinho
│   ├── ImageModal.js   # Modal para ampliar imagens
│   ├── FloatingButton.js   # Botão flutuante do WhatsApp
│   └── FloatingInfoBox.js  # Caixa de informações flutuante
├── data/
│   └── products.js     # Dados dos produtos
├── hooks/
│   ├── useCart.js      # Hook para gerenciar carrinho
│   └── useModal.js     # Hook para gerenciar modais
├── styles/
│   └── index.css       # Estilos CSS
├── App.js              # Componente principal
└── index.js            # Ponto de entrada
```

## ✨ Funcionalidades

- **Design Responsivo**: Adaptação perfeita para todos os dispositivos
- **Carrinho de Compras**: Adicionar/remover produtos
- **Formulário de Contato**: Integração com EmailJS e WhatsApp
- **Galeria de Produtos**: Visualização organizada por categorias
- **Modais Interativos**: Para produtos, carrinho e informações
- **Acessibilidade**: Navegação por teclado e leitores de tela
- **PWA**: Pode ser instalado como aplicativo

## 🛠️ Tecnologias utilizadas

- **React 18**: Framework principal
- **EmailJS**: Envio de emails do formulário
- **CSS3**: Estilização moderna com variáveis CSS
- **Font Awesome**: Ícones
- **Google Fonts**: Tipografia (Inter + Playfair Display)

## 📞 Contato

WhatsApp: (51) 98533-0121
E-mail: contato@marjuconfeitaria.com

---

*Site desenvolvido com foco em acessibilidade, performance e experiência do usuário.*