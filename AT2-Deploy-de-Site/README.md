## 📊 O que deu certo e o que deu errado (Relato de Experiência)

* **O que deu certo:** 
  * A estruturação semântica das 5 páginas fluiu muito bem, permitindo uma organização limpa do conteúdo e excelente legibilidade do código.
  * O menu de navegação funcionou perfeitamente logo nos primeiros testes de rotas relativas, garantindo que o usuário consiga alternar entre as páginas sem quebrar links.
  * A inserção e o redimensionamento das imagens em formato JPG no corpo do site (`<body>`) ficaram harmônicos e esteticamente agradáveis.

* **O que deu errado (e como foi resolvido):**
  * **Problema com caminhos de arquivos:** No início, ao subir o projeto para o GitHub Pages, as imagens e o arquivo CSS não carregaram porque os caminhos continham barras invertidas (`\`) ou referências locais do computador (`C:\...`). 
  * **Solução:** Substituí todos os caminhos para o padrão web utilizando caminhos relativos limpos (ex: `img/nome-da-imagem.jpg` e `css/style.css`), o que resolveu o erro de carregamento no servidor de produção.
  * **Ajustes de responsividade no menu:** Em telas menores (celulares), o alinhamento inicial dos links quebrou. O ajuste foi resolvido revisando o comportamento dos elementos e garantindo o uso correto das tags e classes de suporte.

## 💻 Deploy do projeto

* **Site Publicado (GitHub Pages):** [Clique para acessar]([https://seu-usuario.github.io/at1-site-multipaginas/](https://diogocora2008-blip.github.io/entrega/jogos.html))
* **Repositório do Código-Fonte:** [Acessar no GitHub]([https://github.com/seu-usuario/at1-site-multipaginas](https://github.com/DanielRib1904/portfolio-daniel-lima/tree/main/AT2-Deploy-de-Site/Projeto%20Daniel%20e%20Diogo))

---

[Voltar ao início](https://github.com/seu-usuario/portfolio-usuario)
