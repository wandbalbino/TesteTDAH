# Teste Informativo de Autoavaliação de TDAH

Página web única (HTML + CSS + JavaScript) para autoavaliação **informativa e educativa** de traços associados ao TDAH (Transtorno do Déficit de Atenção com Hiperatividade), baseada nas manifestações descritas pela [Associação Brasileira do Déficit de Atenção (ABDA)](https://tdah.org.br/).

> ⚠️ **Este projeto NÃO é uma ferramenta de diagnóstico.** Ele não substitui avaliação clínica, médica ou psicológica. Serve apenas como instrumento de autorreflexão.

## 🔗 Demo

Abra o arquivo `teste-autoavaliacao-tdah.html` diretamente no navegador, ou publique via GitHub Pages (veja seção [Como publicar](#-como-publicar-com-github-pages) abaixo).

## ✨ Funcionalidades

- 18 perguntas de múltipla escolha, divididas em dois blocos:
  - **Bloco 1 — Desatenção** (9 perguntas)
  - **Bloco 2 — Hiperatividade e Impulsividade** (9 perguntas)
- Opções de resposta em formato de botão (Nunca / Raramente / Frequentemente / Quase Sempre), estilizadas para facilitar o toque em dispositivos móveis
- Cálculo automático da pontuação por bloco, sem recarregar a página
- Classificação informativa em 4 perfis possíveis:
  - Traços predominantemente de Desatenção
  - Traços predominantemente de Hiperatividade e Impulsividade
  - Traços do Tipo Combinado
  - Baixa probabilidade / Padrão convencional
- Exportação do resultado em arquivo **.json**
- Layout 100% responsivo (mobile-first)
- Código único, sem dependências externas ou build steps

## 🗂 Estrutura do projeto

```
.
├── teste-autoavaliacao-tdah.html   # Arquivo único: HTML + CSS + JavaScript
└── README.md                        # Este arquivo
```

## 🚀 Como usar

Não há instalação nem dependências. Basta:

1. Clonar o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Abrir o arquivo `teste-autoavaliacao-tdah.html` em qualquer navegador moderno (Chrome, Firefox, Edge, Safari).

Também é possível colar o código diretamente em um bloco HTML de qualquer CMS (WordPress, Webflow, etc.), já que todo o CSS e JS estão embutidos no próprio arquivo.

## 📌 Como publicar com GitHub Pages

1. Vá em **Settings → Pages** no repositório.
2. Em **Source**, selecione a branch `main` e a pasta `/root`.
3. Salve. O GitHub vai gerar uma URL pública em poucos minutos.
4. Opcional: renomeie o arquivo para `index.html` para que ele carregue automaticamente na raiz do site.

## 🧮 Metodologia de pontuação

Cada pergunta vale de 0 a 3 pontos (Nunca = 0, Raramente = 1, Frequentemente = 2, Quase Sempre = 3), somando no máximo **27 pontos por bloco**.

A nota de corte utilizada é **50% da pontuação máxima do bloco (14 pontos)**. Esse valor foi definido de forma didática para fins de autorreflexão — a ABDA **não publica** uma escala numérica oficial validada para autoaplicação, portanto os resultados não têm valor diagnóstico ou clínico.

## 🛠 Tecnologias utilizadas

- HTML5 semântico
- CSS3 (Grid, Flexbox, variáveis CSS, media queries)
- JavaScript puro (Vanilla JS) — sem frameworks ou bibliotecas externas

## ⚖️ Aviso legal

Este projeto tem finalidade exclusivamente **educativa e informativa**. Os resultados apresentados **não constituem diagnóstico médico ou psicológico**. Pessoas que se identificarem com os itens do teste devem procurar um profissional de saúde qualificado (médico ou psicólogo) para uma avaliação adequada.

## 📄 Licença

Defina aqui a licença do projeto (ex: [MIT](https://choosealicense.com/licenses/mit/)) antes de publicar, caso deseje permitir reuso por terceiros.

## 🤝 Contribuições

Sugestões, correções e melhorias são bem-vindas. Abra uma *issue* ou envie um *pull request*.
