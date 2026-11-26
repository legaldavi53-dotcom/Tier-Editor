# TIER EDITOR — Anime Villains

Aplicação React + Vite para montar rankings de personagens de One Piece, JoJo's Bizarre Adventure, Demon Slayer e Bleach.

## Executar localmente

Requer Node.js 18 ou superior.

```bash
npm install
npm run dev
```

Para gerar a versão de produção:

```bash
npm run build
npm run preview
```

## Recursos

- Biblioteca inicial com os personagens solicitados (incluindo duplicatas/variações explicitadas na lista).
- Busca, filtro por anime e filtro de não classificados.
- Imagens individuais consultadas pela API pública GraphQL do AniList; personagens personalizados aceitam URL própria. Se uma imagem não carregar, aparece um avatar identificador com o nome.
- Drag and drop com mouse, toque nos cards para escolher o tier e gesto de arrastar no celular para mover entre áreas.
- Categorias editáveis: nome, cor, altura, ordem, criação e exclusão.
- Histórico desfazer/refazer, embaralhar disponíveis, limpar classificação e restaurar tiers padrão.
- Vários quadros, título editável, salvamento automático em LocalStorage, importar/exportar JSON e exportar PNG.

## Imagens

A busca automática de retratos precisa de conexão com a internet e depende da disponibilidade/limites da API AniList. Para uma imagem específica, edite/adicone o personagem usando a URL direta da imagem. A aplicação não redistribui arquivos oficiais de anime.

## Dados

Quadros e classificações ficam no navegador atual (LocalStorage). Use **Salvar** para exportar um arquivo JSON e transportar o ranking entre dispositivos.
