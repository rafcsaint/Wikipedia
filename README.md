#Redesign de Artigo da Wikipedia em Glassmorphismo

Este projeto é uma releitura visual e técnica do artigo da Wikipédia **[Antarctic English](https://en.wikipedia.org/wiki/Antarctic_English)**. O foco foi transformar a interface original da Wikipédia em uma experiência moderna utilizando a estética de **Glassmorphism** (Efeito Vidro (ou LiquidGlass).

---

## Características do Projeto

- **Estética Glassmorphism:** Implementação de transparências avançadas com `backdrop-filter: blur(12px)` e bordas semitransparentes para criar um efeito de vidro fosco.
- **Tipografia Editorial:** Combinação das fontes _Lora_ (serifada) para títulos e _Open Sans_ (sans-serif) para o corpo do texto, otimizando a legibilidade e o design.
- **Header Híbrido:** Navegação fixa (sticky) que utiliza desfoque de fundo para manter o contexto do artigo enquanto o usuário faz o scroll.
- **Componentes Modernizados:**
  - **Infobox (Aside):** Reestilizada com sombras suaves e cantos arredondados (`border-radius: 14px`).
  - **Tabelas:** Design limpo com efeitos de _hover_ e bordas suaves.
- **Design Responsivo:** Layout adaptado para telas menores, garantindo que a "infobox" se ajuste perfeitamente em dispositivos móveis.
- **Navegação Suave:** Implementação de `scroll-behavior: smooth` para transições entre as seções do artigo.

---

## Tecnologias Utilizadas

- **HTML5 Semântico:** Uso de tags estruturais como `<main>`, `<article>`, `<aside>` e `<section>` para melhor acessibilidade.
- **CSS3 Moderno:**
  - **Variáveis e Efeitos:** `backdrop-filter`, `rgba` e gradientes lineares para profundidade.
  - **Layout:** Flexbox para alinhamento de componentes de navegação.
  - **Google Fonts:** Integração direta via `@import`.

---

## Sobre o Conteúdo

O artigo documenta o desenvolvimento de um dialeto único na Antártida, incluindo:

- **Mudanças Fonéticas:** A evolução de sotaques em cientistas isolados durante o inverno.
- **Vocabulário Único:** Termos como _"Dingle day"_ (dia de céu limpo) e _"Homer"_ (cerveja caseira).
- **Influências:** Termos derivados do espanhol e de línguas nórdicas devido às expedições históricas.

---

## Como Executar

1.  Clone este repositório:
    ```bash
    git clone [https://github.com/seu-usuario/antarctic-english-glassmorphism.git](https://github.com/seu-usuario/antarctic-english-glassmorphism.git)
    ```
2.  Abra o arquivo `index.html` em seu navegador de preferência.

---

## Licença

Este projeto foi desenvolvido para fins de estudo de UI/UX. O texto original é de propriedade da Wikipédia e seus colaboradores, sob a licença **CC BY-SA 4.0**.
