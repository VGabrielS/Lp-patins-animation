# Landing pages - Snitap Patins 🚀

Esse projeto é uma apresentação de uma landing page animada para uma loja de patins.
## 📌 Status do Projeto
✅ Finalizado
## 📷 Demonstração
![image](https://github.com/user-attachments/assets/f26f4d61-bb84-441f-a72a-8de1ad212679)

## 🔧 Tecnologias utilizadas
- HTML5 semântico
- CSS puro — sem JavaScript, sem build, sem frameworks

Recursos de CSS em destaque:
- **Scroll-driven animations** (`animation-timeline: view()`) para revelar as imagens da galeria conforme entram na tela
- **CSS Nesting** nativo (`&`) para organizar os seletores por seção
- `@keyframes` para o carrossel de palavras no título (hero), o banner com rolagem infinita de logos e o gradiente animado de fundo
- CSS Custom Properties para cores, tipografia e espaçamento (`styles/global.css`)

## 📁 Estrutura do projeto

```
index.html          Página única com toda a estrutura da landing page
styles/
  index.css           Agrega os demais arquivos de estilo (@import)
  global.css           Reset, variáveis de tema e estilos base
  header.css           Cabeçalho (logo e carrinho)
  hero.css             Seção principal, com o título animado e botões de CTA
  banner.css           Faixa com rolagem infinita de logos e gradiente animado
  gallery.css          Galeria de fotos com animação de entrada ao rolar a página
  footer.css           Rodapé com navegação e redes sociais
assets/              Imagens, ícones e ilustrações usados na página
```

## ▶️ Como executar

Por ser um projeto estático (sem build), basta abrir o `index.html` diretamente no navegador ou servir a pasta com qualquer servidor local, por exemplo:

```bash
npx serve .
```

ou, usando a extensão **Live Server** do VS Code, clicando com o botão direito em `index.html` → "Open with Live Server".

> As animações de rolagem (`animation-timeline: view()`) exigem um navegador com suporte a Scroll-driven Animations (Chrome/Edge recentes). Em navegadores sem suporte, as imagens da galeria aparecem sem a animação de entrada.
