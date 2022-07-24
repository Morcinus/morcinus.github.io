# Můj blog

## Jak spustit stránku lokálně:

```bash
# v hlavní directory
docker-compose up
```

## Jak deployovat:

Stačí pushnout do `master` větve

## Jak upravovat stránky:

- Pro upravení layoutu editnout stránku `themes/portio/layouts`
- Pro upravení dat v layoutu změnit `data/`
- Pro přidání/úpravu blog postů používat `content/blog`
- Obrázky k blog postům dávat do `static/images`

## Přidání nové stránky

1. Přidat složku a stránku v `content` např. `playlists/_index.md`
2. Přidat složku a stránku do `themes/portio/layouts` např `playlists/playlists.html`
3. Přidat odkaz v navbaru v `config.toml`
