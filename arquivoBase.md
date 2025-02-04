# Git: Guia Completo para Iniciantes

## Capítulo 1: Introdução ao Git

O Git é um sistema de controle de versão distribuído que permite gerenciar e rastrear alterações em arquivos ao longo do tempo.

### Por que usar Git?

- Controle de versão eficiente
- Trabalho colaborativo
- Histórico completo de alterações
- Backup seguro do código

## Capítulo 2: Instalação e Configuração

### Instalando o Git

Para começar, você precisa instalar o Git em seu computador:

- Windows: Baixe o instalador do site oficial do Git
- Mac: Use o Homebrew com o comando "brew install git"
- Linux: Use o comando "sudo apt-get install git"

### Configuração Inicial

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"
```

## Capítulo 3: Comandos Básicos

### Iniciando um Repositório

```bash
git init            # Inicia um novo repositório
git clone [URL]     # Clona um repositório existente
```

### Comandos Essenciais

- **git status**: Verifica o estado dos arquivos
- **git add**: Adiciona arquivos à área de staging
- **git commit**: Salva as alterações no repositório
- **git push**: Envia alterações para o repositório remoto
- **git pull**: Atualiza seu repositório local

## Capítulo 4: Trabalhando com Branches

Branches permitem desenvolver funcionalidades isoladamente.

### Comandos de Branch

```bash
git branch                  # Lista branches
git branch [nome]          # Cria nova branch
git checkout [nome]        # Muda para outra branch
git merge [branch]         # Une branches
```

## Capítulo 5: Boas Práticas

### Commits

- Faça commits pequenos e frequentes
- Escreva mensagens de commit descritivas
- Use verbos no imperativo nas mensagens

### Workflow

- Mantenha a branch main sempre estável
- Crie branches para novas funcionalidades
- Faça review de código antes de merge

## Capítulo 6: Resolução de Problemas

### Conflitos

Conflitos ocorrem quando duas branches têm alterações diferentes no mesmo arquivo.

### Como resolver conflitos

- Identifique os arquivos em conflito
- Escolha qual versão manter
- Faça commit das alterações

## Capítulo 7: Recursos Avançados

### Git Stash

```bash
git stash           # Salva alterações temporariamente
git stash pop       # Recupera alterações salvas
```

### Git Reset

```bash
git reset --soft HEAD~1    # Desfaz último commit mantendo alterações
git reset --hard HEAD~1    # Desfaz último commit removendo alterações
```

## Conclusão

O Git é uma ferramenta essencial para desenvolvedores modernos. Com prática e dedicação, você dominará seus conceitos e comandos principais.

<aside>
Dica: Pratique regularmente os comandos aprendidos em um projeto pessoal para fixar o conhecimento.

</aside>