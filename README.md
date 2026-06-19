# Conexão IE — Skills para Claude Code

Skills customizadas da [Conexão IE](https://conexaoie.com.br) para uso com o [Claude Code](https://claude.ai/code).

## O que são skills?

Skills são instruções estruturadas que ensinam o Claude a executar tarefas específicas do seu negócio — com contexto, critérios e formatos de saída definidos por você.

## Skills disponíveis

### `conexao-ie-mapeador-comercial`

Qualifica leads e apoia o processo de discovery comercial da Conexão IE.

**O que faz:**
- Gera a ficha de inteligência pré-reunião
- Define a hipótese de produto de entrada com justificativa
- Seleciona as perguntas de discovery por perfil
- Classifica o lead em Tier A, B ou C
- Sinaliza alertas de baixo fit
- Registra resultado pós-reunião

**Como usar no Claude Code:**
```
/conexao-ie-mapeador-comercial

Empresa: [nome]
Segmento: [setor]
Porte: [nº funcionários]
Contato: [nome, cargo]
Como chegou: [evento / indicação / busca ativa]
Interesse declarado: [se houver]
```

## Como instalar uma skill

1. Copie o conteúdo do arquivo `.md` da skill desejada
2. No Claude Code, acesse as configurações de skills do seu projeto
3. Cole o conteúdo como uma nova skill

## Sobre a Conexão IE

18 anos de atuação em inteligência emocional e desenvolvimento humano para organizações. Fundada por Alessandra Gonzaga e Marcelo do Carmo.
