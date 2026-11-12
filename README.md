WebZoo — Plataforma de Educação Ambiental

Projeto multipáginas responsivo desenvolvido na disciplina de **Front-End** do **SENAI "Comendador Santoro Mirone" (Indaiatuba/SP)**, sob orientação do professor Marcos Nunes.

O **WebZoo** é uma plataforma fictícia e educativa do Zoológico de São Paulo voltada à apresentação da fauna brasileira, ao planejamento de visitas e à participação em programas de educação ambiental, integrando HTML5 semântico, CSS3 *mobile-first*, acessibilidade e consumo de APIs públicas em tempo real.

---

## Identificação e Links

* **Estudante:** Enzo Martins dos Reis
* **Turma:** DEV2
* **Link publicado:** https://webzoo-enzomartins.netlify.app/
* **Repositório:** https://github.com/enzoreiz/webzoo-enzomartins

---

## Estrutura de Páginas e Arquivos

O site conta com quatro páginas HTML na raiz, conectadas por cabeçalho, menu de navegação e rodapé idênticos:

* **`index.html` (Início):** Apresenta o propósito do WebZoo (missão, visão e valores), destaque visual da Mata Atlântica, cards das três espécies principais com atalhos para suas fichas, guia rápido das seções, indicadores em números e curiosidades da fauna brasileira.
* **`animais.html` (Animais):** Reúne as fichas educativas completas da **onça-pintada** (*Panthera onca*), do **tucano-toco** (*Ramphastos toco*) e da **capivara** (*Hydrochoerus hydrochaeris*), além de filtros interativos e da legenda oficial do estado de conservação da Lista Vermelha da IUCN.
* **`visite.html` (Visite):** Disponibiliza a previsão do tempo atual no Zoológico de São Paulo, horários de funcionamento, tabela acessível de ingressos, endereço e formas de acesso, dicas de passeio, regras de visitação, recursos de acessibilidade no parque e perguntas frequentes (FAQ).
* **`participe.html` (Participe):** Apresenta os quatro programas de educação ambiental (*Zoo Escola*, *Guardiões da Fauna*, *Noite no Zoo* e *Professor Parceiro*), formulário demonstrativo com preenchimento automático de endereço por CEP e validação por campo, além de uma lista de atitudes de cuidado com a natureza.

### Organização de Pastas

WebZoo_Enzo_Martins/
├── index.html
├── README.md
├── pages/
│   └── animais.html
│   └── participe.html
│   └── visite.html
├── css/
│   └── style.css
├── js/
│   ├── menu.js
│   ├── animais.js
│   ├── clima.js
│   ├── cep.js
│   └── formulario.js
└── assets/
    ├── favicon.png
    └── imagens/
        ├── webzoo_logo.png
        ├── floresta.png
        ├── onca_pintada.png
        ├── tucano_toco.png
        └── capivara.png
