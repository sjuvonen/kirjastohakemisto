KIRJASTOHAKEMISTO
=================

This is the main website for [Kirjastohakemisto](https://hakemisto.kirjastot.fi),
the Finnish Library Database. The website is built as a simple frontend that queries our open API at
[api.kirjastot.fi](https://api.kirjastot.fi). The API serves as the database.

## See it in action
- https://hakemisto.kirjastot.fi
- https://directory.libraries.fi
- https://registret.biblioteken.fi

## Dependencies
- PHP 7.1+
- Node.js (for compiling modified assets)

## Deployment
It is enough to clone this repository and compile the provided assets. Build environment can be
installed by running *npm install* in the project root. After this, the build process can be executed
with *npm run build*.

### Notes
After clearing public/dist from pre-compiled assets, the first build will then fail, complaining about
missing browser translation. To fix this, first run the asset builder in dev mode, *npm run dev*.

## Kirkanta repository family
- [Kirjastohakemisto](https://github.com/libraries-fi/kirjastohakemisto) -- frontend
- [Kirkanta](https://github.com/libraries-fi/kirkanta) -- backend
- [Kirkanta API](https://github.com/libraries-fi/kirkanta-api) -- REST API
- [Kirkanta Widgets](https://github.com/libraries-fi/kirkanta-embed) -- Build embeddable widgets
