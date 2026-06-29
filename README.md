# Clínica Vida e Saúde

Sistema web para clínica médica com agendamento de consultas, autenticação e painel de informações. Construído com HTML, CSS e JavaScript puros.

---

## Páginas

| Arquivo | Descrição |
|---|---|
| `html/index.html` | Landing page principal com carrossel, abas e mapa |
| `html/login.html` | Login por CPF e senha |
| `html/registro.html` | Cadastro de novo paciente |
| `html/agendar.html` | Agendamento de consultas |
| `html/esqueceu.html` | Recuperação de senha |

---

## Tech Stack

- HTML5
- CSS (sem frameworks)
- JavaScript vanilla
- Font Awesome 6.5

---

## Design System

Todas as cores e tokens vivem em `css/variables.css`:

```css
--color-primary: #009688
--color-primary-dark: #00695c
--color-accent: #43cea2
```

Para mudar a paleta da clínica, edite apenas esse arquivo. Dark mode automático via `prefers-color-scheme`.

---

## Estrutura

```
├── css/
│   ├── variables.css       # Tokens de design (cores, sombras, fontes)
│   ├── style.css           # Base compartilhada (forms, botões, sidebar)
│   ├── styleindex.css      # Estilos da home
│   ├── styleagendar.css    # Estilos da página de agendamento
│   ├── stylelogin.css      # Overrides do login
│   ├── styleregistro.css   # Overrides do cadastro
│   └── styleesqueceu.css   # Estilos da recuperação de senha
├── html/
├── images/
└── javascript/
    ├── carrossel.js
    ├── tabs.js
    ├── sidebar.js
    ├── homebar.js
    ├── acessibilidade.js
    └── app.js
```

---

## Como rodar

```bash
git clone https://github.com/37Linard/Clinica-Medica-
```

Abra `html/index.html` no navegador. Não requer servidor.

---

## Acessibilidade

- Widget fixo com opções de alto contraste e texto maior
- Integração com VLibras (Libras)
- Focus rings visíveis em todos os inputs

---

## Contribuindo

Pull requests são bem-vindos. Para mudanças grandes, abra uma issue primeiro.
