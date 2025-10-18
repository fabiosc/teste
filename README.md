# Player de Vídeo HLS

Uma aplicação web simples para reproduzir streams HLS (HTTP Live Streaming) usando HLS.js.

## Funcionalidades

- ✅ Reprodução de streams HLS (.m3u8)
- ✅ Seleção automática de qualidade
- ✅ Seleção manual de qualidade/resolução
- ✅ Suporte nativo para Safari
- ✅ Interface responsiva
- ✅ URLs de exemplo para teste
- ✅ Informações detalhadas do stream

## Como usar

1. Cole uma URL de stream HLS no campo de entrada
2. Clique em "Carregar Vídeo" ou pressione Enter
3. Use os controles de qualidade para ajustar a resolução
4. Ou teste com uma das URLs de exemplo fornecidas

## Compatibilidade

- ✅ Chrome/Edge/Firefox (via HLS.js)
- ✅ Safari (suporte nativo HLS)
- ✅ Dispositivos móveis

## Deployment no Digital Ocean

Esta aplicação está pronta para ser deployada como uma aplicação estática no Digital Ocean App Platform.

### Opção 1: Deploy via GitHub

1. Faça push deste código para um repositório GitHub
2. No Digital Ocean App Platform, crie uma nova app
3. Conecte seu repositório GitHub
4. Configure como "Static Site"
5. O build será automático (não requer build steps)

### Opção 2: Deploy via arquivo ZIP

1. Faça zip dos arquivos (`index.html`, `README.md`, etc.)
2. No Digital Ocean App Platform, faça upload do ZIP
3. Configure como "Static Site"

### Configurações recomendadas:

- **Build Command**: Deixe vazio (não necessário)
- **Output Directory**: `/` (root)
- **Index Document**: `index.html`
- **Error Document**: `index.html`

## Arquivos inclusos

- `index.html` - Aplicação principal
- `README.md` - Este arquivo de documentação
- `.gitignore` - Arquivos a serem ignorados pelo Git
- `app.yaml` - Configuração para Digital Ocean App Platform

## Tecnologias usadas

- HTML5 Video API
- HLS.js para compatibilidade com navegadores
- CSS3 para styling responsivo
- Vanilla JavaScript

## Licença

MIT License