# Assets do KalangoOS

Marca, ícones dos apps, sons do sistema e papéis de parede do [KalangoOS](https://github.com/kalangoos/kalangoos).

| Pasta | O quê | Licença |
|---|---|---|
| `brand/` | Logos, símbolo, ícone e variantes (PNG/SVG) | Marca (`LICENSE-brand.txt`) |
| `icons/kalango/` | Ícones dos apps do sistema | Ver `ATTRIBUTION.md` |
| `sounds/kalango/` | Sons de UI (`.oga`, tema freedesktop) | CC0-1.0 |
| `wallpapers/` | Papéis de parede (inclui legado `lunar-*`) | Ver `ATTRIBUTION.md` |

O monorepo [`kalangoos/kalangoos`](https://github.com/kalangoos/kalangoos) consome estes arquivos em `assets/` e `wallpapers/` (submodule ou sync).

**Não inclui** vídeos Remotion nem capturas de marketing — esses ficam no repositório privado `kalangoos/remotion`.

## Sync com o código

```sh
# no monorepo, com submodule:
git submodule update --init --recursive
# ou copiar:
# rsync -a brand/ icons/ sounds/ ../kalangoos/assets/
# rsync -a wallpapers/ ../kalangoos/wallpapers/
```

## English

Brand pack, system app icons, UI sounds (CC0) and wallpapers for KalangoOS. Brand is not open-licensed (`LICENSE-brand.txt`). Remotion promo media is private and lives elsewhere.
