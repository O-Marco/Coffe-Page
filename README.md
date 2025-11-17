# ☕ Dev Teste - Landing Page de Cafeteria

Este projeto é uma **landing page** com tema de cafeteria, desenvolvida para treinar habilidades em **HTML5** e **CSS3**. Apresenta um layout moderno e responsivo, ideal para um site promocional ou portfólio.


## ✨ Funcionalidades

* **Header Fixo**: O cabeçalho e a barra de navegação permanecem fixos no topo da tela (cláusula `.header`), garantindo acesso fácil aos links.
* **Design Responsivo**: O uso de **Flexbox** e **CSS Grid** (especialmente em `.box-container`) permite que a página se adapte bem a diferentes tamanhos de tela.
* **Menu em Destaque**: A seção de menu (`#menu`) exibe os itens em um layout de grid (`repeat(auto-fit, minmax(30rem, 1fr))`), com um efeito de hover chamativo que inverte as cores.
* **Variáveis CSS**: Utilização de variáveis CSS (`:root`) para gerenciar cores e valores de borda, facilitando futuras alterações de tema.
* **Efeitos de Transição**: Transições suaves (`transition: 0.2s linear;`) em links e botões, melhorando a experiência do usuário.

## 🛠️ Tecnologias Utilizadas

O projeto foi construído puramente com:

* **HTML5**: Estruturação semântica do conteúdo.
* **CSS3**: Estilização e layout, incluindo **gradientes** no `body` e uso intensivo de **variáveis CSS**.
* **Fontes Google**: A fonte principal utilizada é a **"Roboto"**.
* **Iconografia**: Ícones fornecidos por **Icons8** para busca, carrinho e mídias sociais.

---

## 📄 Estrutura do Arquivo CSS (style.css)

O arquivo de estilos está organizado em seções lógicas:

| Seção | Descrição |
| :--- | :--- |
| **`:root`** | Variáveis globais para cores (`--main-color`, `--bg`, etc.) e tamanho de fonte base. |
| **`*`** | Reset básico e configurações globais (margens, padding, `text-transform: capitalize`, etc.). |
| **`body`** | Estilo de fundo com gradiente e cor de texto. |
| **`.header` / `.navbar`** | Estilização do cabeçalho fixo e da navegação centralizada. |
| **`.home-container`** | Estilo da primeira seção (hero) com imagem de fundo. |
| **`.title`** | Estilo para títulos de seção padronizados. |
| **`.about`, `.menu`, `.review`** | Layout e estilo específicos para cada seção de conteúdo principal. |
