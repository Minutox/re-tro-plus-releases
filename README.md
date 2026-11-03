# Re TRÔ+ para Android

Canal público de distribuição do Re TRÔ+, interface retrô para organizar e abrir jogos com emuladores no Android.

## Instalar ou atualizar

1. Baixe o APK na seção [Releases](https://github.com/Minutox/re-tro-plus-releases/releases/latest).
2. Instale sobre a versão anterior, sem desinstalar, para preservar os dados do aplicativo. Faça backup antes.
3. No aplicativo, abra **Opções → Emuladores → Buscar atualizações**.

A partir da 0.19-beta, o canal do próprio Re TRÔ+ já vem configurado.

- Manifesto de versões: [updates.json](https://raw.githubusercontent.com/Minutox/re-tro-plus-releases/main/updates.json).
- APKs assinados e arquivos SHA-256 ficam em Releases.
- Algumas fontes de emuladores exigem conferência manual. Os núcleos e recursos do RetroArch são gerenciados pelo próprio emulador.
- As instalações são confirmadas pelo usuário; não há instalação silenciosa.

## Conteúdo

O APK inclui sete instaladores de emuladores, com créditos e licenças preservados no pacote: Snes9x EX+, NES.emu, GBA.emu, GBC.emu, MD.emu, PPSSPP e RetroArch. Os emuladores são instalados como aplicativos separados.

Este canal não contém jogos, BIOS, saves, favoritos pessoais ou chaves de assinatura. O APK contém os recursos visuais e sonoros do aplicativo. Não há publicação do diretório de desenvolvimento neste repositório.

Esta é uma beta testada no Android virtual. Desempenho e controles no RP5 físico ainda precisam de validação. Não é o port Linux para XU Mini M.

## Novidades da 0.20

- **Busca em lote:** fila persistida, pausa, cancelamento, retomada e revisão de resultados. Libretro sem cadastro; ScreenScraper opcional com acesso autorizado. Dados existentes são preservados por padrão.
- **Temas e layouts:** tema original, Arcade Neon e Sala Clássica; lista, grade e vitrine. Prévia reversível, pacotes próprios `.retrotheme` e exportação.
- **Mídias separadas:** capa, screenshot, logotipo, vídeo e manual por jogo. Preferência de exibição e leitor PDF interno com navegação por páginas.

A fila não inicia sozinha. Vídeos e manuais podem ser associados localmente. As disponibilidades de imagens e informações variam por sistema/provedor. O catálogo pessoal não é incluído neste repositório.

As instruções completas estão no arquivo NOTAS-DA-VERSAO.txt do release. Testes no computador e Android virtual; ainda não é uma validação física no RP5.
