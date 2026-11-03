# Temas do Re TRÔ+

O Android 0.22 ou superior consulta `catalog.json` pela galeria de temas.
Os temas baixados funcionam offline. Novos temas não exigem outro APK.

Publique pacote `.retrotheme` e prévia nesta pasta, depois acrescente a entrada
no catálogo mantendo as anteriores. Campos: id (igual ao pacote), name,
version (inteiro), bytes, sha256 do pacote exato, url, preview.
As URLs devem usar `https://raw.githubusercontent.com/Minutox/re-tro-plus-releases/main/themes/`.

O pacote segue o formato declarativo `re-tro-theme`, formatVersion 1,
com theme.id custom-..., nome, autor, version, layout list/grid/showcase,
typography pixel/normal, palette com accent/background/panel/text/muted/highlight
em hexadecimal e fundo opcional PNG/JPEG/WebP incorporado em data URL.
Limite 1,2 MB por pacote. Não são aceitos scripts ou CSS arbitrários.
Para atualizar, aumente version e recalcule bytes/sha256. Publique o catálogo por último.

Dragon Ball — Aventura Z é um tema de fã sem vínculo oficial com a série.
