# 📋 Comandos de Atalhos do Neovim

## 🔑 Leader Key
O leader key está configurado como: **`<espaço>`** (`<leader>`)

---

## ⌨️ Modo Insert
| Atalho | Ação |
|--------|------|
| `jk` | Sair do modo insert (equivalente a ESC) |

---

## 🔍 Busca e Navegação
| Atalho | Ação |
|--------|------|
| `<leader>nh` | Limpar highlights de busca |
| `<leader>ff` | Fuzzy find files (Telescope) |
| `<leader>fr` | Buscar arquivos recentes |
| `<leader>fs` | Buscar string no diretório (live grep) |
| `<leader>fc` | Buscar string sob o cursor |
| `<leader>ft` | Buscar TODOs |
| `<leader>fk` | Buscar keymaps |

---

## 📝 Números
| Atalho | Ação |
|--------|------|
| `<leader>+` | Incrementar número |
| `<leader>-` | Decrementar número |

---

## 🪟 Gerenciamento de Janelas
| Atalho | Ação |
|--------|------|
| `<leader>sv` | Dividir janela verticalmente |
| `<leader>sh` | Dividir janela horizontalmente |
| `<leader>se` | Igualar tamanho das janelas |
| `<leader>sx` | Fechar janela atual |
| `<leader>sm` | Maximizar/minimizar janela |

---

## 📑 Abas
| Atalho | Ação |
|--------|------|
| `<leader>to` | Abrir nova aba |
| `<leader>tx` | Fechar aba atual |
| `<leader>tn` | Próxima aba |
| `<leader>tp` | Aba anterior |
| `<leader>tf` | Abrir buffer atual em nova aba |

---

## 📁 Navegador de Arquivos (NvimTree)
| Atalho | Ação |
|--------|------|
| `<leader>ee` | Toggle file explorer |
| `<leader>ef` | Toggle file explorer no arquivo atual |
| `<leader>ec` | Colapsar file explorer |
| `<leader>er` | Atualizar file explorer |

---

## 🔧 LSP (Language Server Protocol)
| Atalho | Ação |
|--------|------|
| `gR` | Mostrar referências (Telescope) |
| `gD` | Ir para declaração |
| `gd` | Mostrar definição LSP |
| `gi` | Mostrar implementações (Telescope) |
| `gt` | Mostrar definições de tipo (Telescope) |
| `<leader>ca` | Ver ações de código disponíveis |
| `<leader>rn` | Renomear inteligente |
| `<leader>D` | Mostrar diagnósticos do buffer (Telescope) |
| `<leader>d` | Mostrar diagnósticos da linha |
| `[d` | Ir para diagnóstico anterior |
| `]d` | Ir para próximo diagnóstico |
| `K` | Mostrar documentação sob o cursor |
| `<leader>rs` | Reiniciar LSP |

---

## ⚠️ Trouble (Diagnósticos)
| Atalho | Ação |
|--------|------|
| `<leader>xw` | Abrir diagnósticos do workspace |
| `<leader>xd` | Abrir diagnósticos do documento |
| `<leader>xq` | Abrir quickfix list |
| `<leader>xl` | Abrir location list |
| `<leader>xt` | Abrir TODOs no Trouble |

---

## 🎨 Formatação
| Atalho | Ação |
|--------|------|
| `<leader>mp` | Formatar arquivo ou seleção (modo visual) |

---

## 🔀 Git (Gitsigns)
| Atalho | Ação |
|--------|------|
| `]h` | Próximo hunk |
| `[h` | Hunk anterior |
| `<leader>hs` | Stage hunk |
| `<leader>hr` | Reset hunk |
| `<leader>hS` | Stage buffer |
| `<leader>hR` | Reset buffer |
| `<leader>hu` | Desfazer stage hunk |
| `<leader>hp` | Preview hunk |
| `<leader>hb` | Blame linha (completo) |
| `<leader>hB` | Toggle blame linha |
| `<leader>hd` | Diff this |
| `<leader>hD` | Diff this ~ |

---

## 🐙 LazyGit
| Atalho | Ação |
|--------|------|
| `<leader>lg` | Abrir LazyGit |

---

## 🔎 Telescope (dentro do modo insert)
| Atalho | Ação |
|--------|------|
| `<C-k>` | Mover para resultado anterior |
| `<C-j>` | Mover para próximo resultado |
| `<C-q>` | Enviar selecionados para quickfix + Trouble |
| `<C-t>` | Abrir no Trouble |

---

## ✅ Configuração Python

### ✅ **Python está configurado!**

#### Servidor LSP:
- **Pyright** - Instalado e configurado (ver `lua/josean/plugins/lsp/mason.lua`)

#### Formatadores:
- **isort** - Organização de imports
- **black** - Formatação de código
- Configurado para formatar automaticamente ao salvar (ver `lua/josean/plugins/formatting.lua`)

#### Linter:
- **pylint** - Instalado via Mason

#### Atalhos disponíveis para Python:
Todos os atalhos LSP acima funcionam com Python:
- `gd` - Ir para definição
- `K` - Ver documentação
- `<leader>ca` - Ações de código (imports, refatoração, etc.)
- `<leader>mp` - Formatar código Python
- `<leader>d` - Ver erros/warnings da linha
- `]d` / `[d` - Navegar entre erros

---

## 📝 Notas
- O formatação automática está ativada ao salvar para Python
- Os formatadores `isort` e `black` são executados em sequência
- O LSP Pyright fornece autocomplete, type checking e outras funcionalidades inteligentes

