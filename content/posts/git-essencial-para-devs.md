---
title: "👩‍💻 Git Essencial: Comandos que Todo Desenvolvedor Precisa Saber"
date: 2024-01-26T10:00:00-03:00
tags: ["git", "github", "version-control", "tutorial", "iniciantes"]
summary: "Guia prático com os comandos Git mais importantes para desenvolvedores iniciantes. Aprenda a versionar seu código como um profissional!"
---

Se você está começando na programação, dominar o Git é tão importante quanto aprender a codar. Neste guia, vou compartilhar os comandos essenciais que uso diariamente.

## 🔍 O que é Git?

Git é um **sistema de controle de versão distribuído** criado por Linus Torvalds (o mesmo criador do Linux). Ele permite:

- 📚 **Histórico completo**: Veja todas as mudanças no seu código
- 🔀 **Branches**: Trabalhe em múltiplas features simultaneamente
- 🤝 **Colaboração**: Várias pessoas no mesmo projeto
- ↩️ **Viajar no tempo**: Volte para qualquer versão anterior

## 🎯 Comandos Básicos (80% do uso diário)

### 1. Configuração Inicial
```bash
# Configure sua identidade
git config --global user.name "Graziele West"
git config --global user.email "seu@email.com"

# Configure editor preferido (opcional)
git config --global core.editor "code --wait"
