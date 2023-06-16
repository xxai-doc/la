<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

Commendatur ut installare nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) primum, ac deinde `direnv allow` post ingressum indicem ( [in .envrc](https://github.com/xxai-art/doc/blob/main/.envrc) exsecutioni mandabitur automatice post ingressum indicem).

Sensus est: Sinica translatio in Iaponica, Coreanica, Anglica, Anglica translatio ad omnes alias linguas. Si Sinica et Anglica tantum sustinere vis, tantum scribere potes `zh: en` .

Sensus est: Sinica translatio in Iaponica, Coreanica, Anglica, Anglica translatio ad omnes alias linguas. Si Sinica et Anglica tantum sustinere vis, tantum scribere potes `zh: en` .

* [ante-finem codice](https://github.com/xxai-art/web)
* [Lingua sarcinas pro situ totum](https://github.com/xxai-art/web/tree/main/i18n)
* [Linguae sarcinae pro login modules](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [Website Multilingual Documenta](https://github.com/xxai-doc)

Ante-finem programmatio linguae [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) est, quae nonnullas notas addit in syntaxi coffeescripte, vide [./coffee_plus.md](./coffee_plus.md) .

## Internationalization of websites and documents

Aedificare in sequentibus III projects

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  Suffixum est `.mdt` , syntaxi similis uti potes `<+ ./coffee_plus/import.js>` ad lima externa referre, et notam generare cum suffixo `.md` .

* [@w5/trmd](https://www.npmjs.com/package/@w5/trmd)

  Markdown translatio non codicibus et nexus transferet, et sententias interpretabitur. Si translatio mutata est sed textus originalis non modificatur, iterum exsequens modificationem translationis non scribet.

* [@w5/i18n](https://www.npmjs.com/package/@w5/i18n)

  Lima linguae in translatione `yaml` generatae websites.

### Document Translation Automation mandatum

Vide codicem repositio [xxai-art/doc](https://github.com/xxai-art/doc)

Commendatur ut installare nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) primum, ac deinde `direnv allow` post ingressum indicem ( [in .envrc](https://github.com/xxai-art/doc/blob/main/.envrc) exsecutioni mandabitur automatice post ingressum indicem).

Ad evitandum basin amplissimum codicem in centenas linguas translatum, codicem separatum basi uniuscuiusque linguae creavi et organizationem feci ut basis codicem reponerem.

Ponens ambitus variabilis `GITHUB_ACCESS_TOKEN` ac deinde cursus [create.github.coffee](https://github.com/xxai-art/doc/blob/main/create.github.coffee) automatice codicem repositum creabit.

Utique etiam in codice basi ponere potes.

Translation scriptum reference [run.sh](https://github.com/xxai-art/doc/blob/main/run.sh)

Scriptum codicem sic interpretatur:

[bunx](https://bun.sh/docs/cli/bunx) repositum est pro npx, quod est velocius. Utique, si PLACENTA non habes, loco `npx` uti potes.

`bunx mdt zh` reddit `.mdt` in directorio zh ut `.md` , vide tabellas 2 nexus infra

* [coffee_plus.mdt](https://github.com/xxai-doc/zh/blob/main/coffee_plus.mdt)
* [coffee_plus.md](https://github.com/xxai-doc/zh/blob/main/coffee_plus.md)

`bunx i18n` est nucleus code pro translatione (si modo `nodejs` inauguratus habes, sed `bun` et `direnv` non inauguratus, currere etiam `npx i18n` interpretari potes).

Parse [i18n.yml](https://github.com/xxai-art/doc/blob/main/i18n.yml) , figura `i18n.yml` in hoc documento talis est:

```
en:
zh: ja ko en
```

Sensus est: Sinica translatio in Iaponica, Coreanica, Anglica, Anglica translatio ad omnes alias linguas. Si Sinica et Anglica tantum sustinere vis, tantum scribere potes `zh: en` .

Ultimum est [gen.README.coffee](https://github.com/xxai-art/doc/blob/main/gen.README.coffee) , quod extrahit contentum inter titulum principalem et primam subtilissimam cuiusque linguae `README.md` ad generandum ingressum `README.md` . Codex valde simplex est, te ipsum intueri potes.

Google API translatione gratis adhibetur. Si Google accedere non potes, configurare et procuratorem pone, ut:

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```

Scriptum translatio latibulum translatum generabit in directorio `.i18n` , illud cum `git status` reprehendo et adde in repositorio codice ad vitandas translationes iteratas.

Curre quaeso `bunx i18n` quotienscumque versionem mutare ad latibulum renovandum.

Si textus originalis et translatio simul modificantur, cella confundetur, ergo si mutare vis, unum tantum mutare potes, et deinde `bunx i18n` ad cella renovare.
