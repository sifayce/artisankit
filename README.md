# ArtisanKit

> Open-source toolkit for French-speaking tradespeople (plumbers, electricians, heating engineers...). Free, MIT-licensed, built in the open.

**Status: planning phase.** The repository has just been created. The roadmap below describes what will be built first. Contributions and feedback are welcome from day one.

## Why

Most tradespeople in France rely on paid SaaS tools for quotes, invoices and customer requests. Free, open-source, French-language alternatives are almost nonexistent. ArtisanKit aims to fill that gap with simple, self-hostable building blocks.

The project is started by a working plumber (Reims, France) and will be tested on real day-to-day business needs.

## Planned modules

1. **Quote & invoice generator** - produces quotes (devis) and invoices (factures) with the legal mentions required in France (SIRET, VAT status, payment terms, late-payment penalties, etc.). Export to PDF.
2. **Request intake assistant** - an AI-assisted form/chat (built on the Claude API) that collects an intervention request: urgency, fault type, address, photos, availability. Outputs a clean summary for the tradesperson.
3. **Local-service website template** - a fast, static, SEO-friendly site template for emergency/local services, deployable for free (GitHub Pages / Netlify).

## Roadmap

- [ ] **v0.1** - Repository structure, license, contribution guide, data model for quotes/invoices
- [ ] **v0.2** - Quote generator (CLI + simple web UI), PDF export, unit tests
- [ ] **v0.3** - Invoice generator with legal mentions checklist
- [ ] **v0.4** - Intake assistant prototype (prompt design, test cases, evaluation set in French)
- [ ] **v0.5** - Website template + deployment guide
- [ ] **v1.0** - Documentation in French and English, first stable release

## Contributing

Issues, ideas and pull requests are welcome. Good first issues will be labelled `good first issue`.

## License

[MIT](LICENSE)
