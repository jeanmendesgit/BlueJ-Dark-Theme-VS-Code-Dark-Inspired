# BlueJ Dark Theme — VS Code Dark+ Inspired

![BlueJ](https://img.shields.io/badge/BlueJ-Theme-1e1e1e?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/status-beta-yellow?style=flat-square)

Um tema escuro para o **BlueJ** inspirado na paleta **VS Code Dark+**. Feito para quem passa horas programando no BlueJ e quer uma experiência visual mais confortável — e bonita — sem sair do ambiente.

---

## 📸 Preview

> _Adicione aqui screenshots do tema em ação:_
>
> - Editor de código com syntax highlighting
> - Diagrama de classes
> - Debugger
> - Terminal
> - Object Bench

---

## 🎨 Paleta de Cores

O tema usa a paleta oficial do **VS Code Dark+**, garantindo consistência visual:

| Uso | Cor | Hex |
|-----|-----|-----|
| Fundo principal | ![#1e1e1e](https://via.placeholder.com/15/1e1e1e/000000?text=+) | `#1e1e1e` |
| Fundo secundário | ![#252526](https://via.placeholder.com/15/252526/000000?text=+) | `#252526` |
| Painéis / Cards | ![#2d2d30](https://via.placeholder.com/15/2d2d30/000000?text=+) | `#2d2d30` |
| Bordas | ![#3e3e42](https://via.placeholder.com/15/3e3e42/000000?text=+) | `#3e3e42` |
| Texto padrão | ![#d4d4d4](https://via.placeholder.com/15/d4d4d4/000000?text=+) | `#d4d4d4` |
| Texto secundário | ![#858585](https://via.placeholder.com/15/858585/000000?text=+) | `#858585` |
| Azul (seleção/links) | ![#0e639c](https://via.placeholder.com/15/0e639c/000000?text=+) | `#0e639c` |
| Azul claro (tipos) | ![#569cd6](https://via.placeholder.com/15/569cd6/000000?text=+) | `#569cd6` |
| Verde-água (classes/objetos) | ![#4ec9b0](https://via.placeholder.com/15/4ec9b0/000000?text=+) | `#4ec9b0` |
| Rosa (keywords/controle) | ![#c586c0](https://via.placeholder.com/15/c586c0/000000?text=+) | `#c586c0` |
| Amarelo (strings especiais) | ![#dcdcaa](https://via.placeholder.com/15/dcdcaa/000000?text=+) | `#dcdcaa` |
| Laranja (strings) | ![#ce9178](https://via.placeholder.com/15/ce9178/000000?text=+) | `#ce9178` |
| Verde (comentários) | ![#6a9955](https://via.placeholder.com/15/6a9955/000000?text=+) | `#6a9955` |
| Vermelho (erros) | ![#f44747](https://via.placeholder.com/15/f44747/000000?text=+) | `#f44747` |
| Vermelho claro (avisos) | ![#f48771](https://via.placeholder.com/15/f48771/000000?text=+) | `#f48771` |
| Azul claro (variáveis) | ![#9cdcfe](https://via.placeholder.com/15/9cdcfe/000000?text=+) | `#9cdcfe` |
| Verde claro (números) | ![#b5cea8](https://via.placeholder.com/15/b5cea8/000000?text=+) | `#b5cea8` |
| Azul ciano (constantes) | ![#4fc1ff](https://via.placeholder.com/15/4fc1ff/000000?text=+) | `#4fc1ff` |

---

## ✨ O que mudou

- 🌑 **Fundo escuro** em toda a interface (interface, editor, terminal)
- 🎨 **Syntax highlighting** com a paleta VS Code Dark+
- 🧩 **Diagrama de classes** com cores adaptadas para fundo escuro
- 💻 **Terminal** e **Code Pad** integrados ao tema
- 📑 **Abas do editor** com indicadores claros (selecionada, com erro, hover)
- 🎯 **Menus de contexto** estilizados

---

## 📦 Instalação

### Método 1: Substituir arquivos (recomendado)

1. **Feche o BlueJ** completamente.
2. Localize a pasta de estilos do BlueJ. Normalmente fica em:
   - **Windows:** `C:\Program Files\BlueJ\lib\stylesheets\`
3. **Faça backup** da pasta `stylesheets` original.
4. Copie os arquivos `.css` deste repositório para a pasta `stylesheets`.
5. Abra o BlueJ novamente.

---

## 📁 Arquivos Modificados

| Arquivo | Descrição |
|---------|-----------|
| `dialogs.css` | Diálogos (About, Preferences, Export, etc) |
| `editor-banners.css` | Banners do editor (undo/delete) |
| `editor-catalogue.css` | Catálogo lateral do editor |
| `editor-error-bar.css` | Barra de erros do editor |
| `editor-error-fix.css` | Sugestões de correção de erros |
| `editor-expression.css` | Estilo de expressões e slots |
| `editor-help.css` | Painel de ajuda de teclas |
| `editor-menu.css` | Menu bar e menus de contexto |
| `editor-selection.css` | Destaques de seleção |
| `editor-slot-choice.css` | Slots de escolha |
| `editor-suggestions.css` | Auto-complete |
| `editor-tabs.css` | Abas do editor |
| `flow.css` | Editor antigo (flow) |
| `frame-style.css` | Estilo geral dos frames (principal) |
| `inspectors.css` | Inspectors de objetos |
| `java-colors.css` | Cores de tokens Java + escopo |
| `moe.css` | Editor novo (Moe) |
| `pkgmgrframe.css` | Janela principal do BlueJ |
| `popup.css` | Popups e tooltips de erro |
| `shared.css` | Ícones compartilhados |
| `terminal.css` | Terminal |

---

## ⚠️ Compatibilidade

- **Testado em:** BlueJ **6.0.1** (lançado em 4 de setembro de 2026)
- **Sistemas testado:** Windows
---

## ⚠️ Aviso

> **Este é um projeto NÃO OFICIAL.**
>
> Não possui qualquer vínculo, afiliação ou endosso do time oficial do BlueJ.
>
> **Status:** versão **BETA** — em testes ativos.
>
> **Podem existir bugs**, elementos com contraste ruim, partes da UI não estilizadas, ou comportamentos inesperados dependendo da versão do BlueJ e do sistema operacional.
>
> **Desenvolvido e testado na versão 6.0.1 do BlueJ.**
>
> Use por sua conta e risco. **Sempre faça backup** dos arquivos originais antes de substituí-los (veja a seção de instalação).
>
> Se encontrar algum problema, por favor abra uma **issue** com detalhes (versão do BlueJ, sistema operacional, screenshot) — isso ajuda muito a melhorar o tema. 🐛

---

## 🐛 Problemas Conhecidos

- **Terminal:** o `TextArea` nativo do JavaFX tem limitações de estilo. Algumas regras usam `!important` para sobrescrever o tema Modena padrão — se o BlueJ atualizar a versão do JavaFX, pode ser necessário ajustar.
- **Caret do editor:** a cor do caret é definida no código Java (não apenas no CSS), então não é totalmente customizável via stylesheet.
- **Alguns `!important`:** foram usados para sobrescrever regras internas do BlueJ. Se preferir uma versão "limpa", substitua por seletores mais específicos.

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Se você:

- Encontrou um bug visual
- Tem sugestões de melhoria
- Quer adicionar suporte a uma versão diferente do BlueJ

Abra uma **issue** ou envie um **pull request**. 😄

---

## 📜 Licença

MIT — use, modifique e compartilhe livremente.

Baseado no tema [VS Code Dark+](https://github.com/microsoft/vscode) e no stylesheet original do [BlueJ](https://www.bluej.org/).

---

## 🙏 Agradecimentos

- **Microsoft** — pela paleta VS Code Dark+
- **Time do BlueJ** — pelo ambiente e pelo stylesheet base
- **Comunidade JavaFX** — pela documentação e exemplos de CSS

---

## ⭐ Se curtir, deixa uma estrela!

Se este tema te ajudou, dá uma ⭐ no repositório — ajuda outros usuários do BlueJ a encontrarem.
