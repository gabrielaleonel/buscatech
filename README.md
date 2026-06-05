# Buscatech

Ferramenta para pesquisar vagas de **estágio em tecnologia** na plataforma Gupy.

## Como usar

```bash
# Clone o repositório
git clone https://github.com/gabrielaleonel/buscatech.git
cd buscatech

# Inicie o servidor
node server.js

# Acesse no navegador
# http://localhost:8081
```

Clique em **"Iniciar busca"** e aguarde. O programa percorre dezenas de palavras-chave, filtra somente vagas que são **estágio + tecnologia**, remove duplicatas e exibe tudo em uma lista.

## Funcionalidades

- Pesquisa com múltiplas palavras-chave simultaneamente
- Filtragem inteligente (título + descrição + tipo da vaga)
- Controles: Iniciar, Pausar, Continuar, Parar
- Status em tempo real com contadores
- Abas separadas: Aprovadas, Ignoradas, Duplicadas, Revisar
- Exportação CSV (compatível com Excel)
- Persistência local (fecha e abre sem perder dados)
- Links clicados ficam roxos permanentemente

## Arquivos

| Arquivo | Descrição |
|---|---|
| `index.html` | Interface completa (HTML + CSS + JS) |
| `server.js` | Servidor proxy Node.js |
| `package.json` | Configuração do pacote npm |

## Instalação via npm

```bash
npm install @gabrielaleonel/buscatech
```

## Licença

MIT
