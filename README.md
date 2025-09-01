# 📚 AluraBooks  

Projeto de um site fictício de livraria online inspirado no **AluraBooks**, desenvolvido com **HTML, CSS e JavaScript**.  
O foco foi aplicar boas práticas de **semântica, responsividade e usabilidade**, organizando a estrutura para funcionar corretamente em **mobile e desktop**.  

---

## 🎯 O que foi feito  

- **Organização do HTML**:  
  - Corrigida a hierarquia das listas (`<ul>` e `<li>`).  
  - Removido uso incorreto de `<li>` fora de listas.  
  - Ajuste nas tags `<img />` (autocontidas, sem `</img>`).  
  - Estrutura do **header** dividida em três blocos:
    1. Menu hamburguer (mobile)  
    2. Logo + título  
    3. Navegação (menu desktop + ícones de usuário/carrinho)  

- **Menu Hamburguer (mobile)**  
  - Criado com **checkbox + label**, alternando a exibição da lista de categorias.  
  - Ícone muda dinamicamente entre **Menu.svg** e **Menu Aberto.svg**.  

- **Menu Desktop**  
  - Opções visíveis em telas maiores (>= 1024px).  
  - Categorias expansíveis com `input[type=checkbox]`.  
  - Efeito **hover** para melhorar a experiência do usuário.  

- **Responsividade**  
  - Mobile-first (primeiro pensado para telas pequenas).  
  - Media queries para **tablet (1024px)** e **desktop widescreen (1728px)**.  
  - Ajuste de exibição de textos, títulos e menus conforme a tela.  

- **Estilo e identidade visual**  
  - Uso de variáveis CSS (`--branco`, `--preto`, `--laranja`, `--azul-degrade`).  
  - Fontes do Google Fonts: **Poppins** e **Josefin Sans**.  
  - Gradientes aplicados em textos e botões.  

- **Carrosséis**  
  - Implementação do **Swiper.js** para exibir os livros e autores em formato dinâmico.  

- **Rodapé**  
  - Estrutura organizada com colunas de links, exibidas somente em telas grandes.  
  - Mobile mostra apenas o título `Grupo Alura`.  

---

## 🛠️ Tecnologias utilizadas  

- **HTML5** (semântica e estrutura)  
- **CSS3** (responsividade, variáveis, gradientes)  
- **JavaScript** (Swiper.js para carrosséis)  
- **Google Fonts** (Poppins e Josefin Sans)  

---

## 📂 Estrutura do projeto  

```

📁 projeto-alurabooks
┣ 📂 img           # Imagens e ícones (logo, menu, favoritos, etc.)
┣ 📂 css
┃ ┣ reset.css      # Reset de estilos
┃ ┗ styles.css     # Estilos principais
┣ index.html       # Estrutura do site
┗ README.md        # Documentação

````

---

✍️ Desenvolvido com foco em **responsividade, semântica e boas práticas**.# Alurabook
