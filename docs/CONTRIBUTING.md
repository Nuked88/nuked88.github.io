## [PATCH ITA\] Cult of the Lamb: ITALIAN LANGUAGE - LINGUA ITALIANA

Salve Ragazzi,
come avrete capito dal titolo ho creato una traduzione italiana di Cult of the Lamb in modo che sia usufruibile anche da chi non mastica così bene l'inglese o da chi vuole avere una maggior immersione nel gioco.
E' assolutamente in uno stadio iniziale per cui vi prego di leggere quanto segue. 

### Importante! 
Essendo una traduzione per lo più automatica (con per ora solo circa il 10% di frasi rivisitate a mano) sappiate che [b]non accetto critiche se alcune (o molte!) frasi non hanno alcun senso. [/b]
[u]Sono bene accette [/u],invece ,segnalazioni di queste ultime di modo che si possano correggere.
Ci sto lavorando ma il tempo e di conseguenza la voglia sono tiranni!

A tal proposito ho creato un [FILE EXCEL](https://1drv.ms/x/s!Ao81reUujmbCs-V3KOFRG1KXal11Ug?e=6PPw5x) con la colonna delle traduzioni manuali editabile da chiunque!

##### NOTA 
Vi prego di non criticare in nessun modo gli sviluppatori per non aver ancora implementato una traduzione ufficiale italiana, vi ricordo infatti che l'italiano rappresenta solo lo  [0,75%](https://store.steampowered.com/hwsurvey)  dei linguaggi utilizzati sulla piattaforma Steam. E questo fa si che rappresenti purtroppo un linguaggio secondario da implementare qui.

Spero che Steam si diffonda sempre più in italia di modo che questa percentuale possa crescere portando la considerazione delle SH per la nostra lingua a dei livelli decenti.

[E' stato comunque detto](https://steamcommunity.com/app/1313140/discussions/0/3448087938660044962/#c3448087938660390558/) che l'italiano potrebbe essere introdotto in futuro, ma senza riferimenti a nessuna data in particolare.

### Tool usati 

* La traduzione è stata fatta con l'AI sia con il modello nllb-200-distilled-1.3B in locale sia utilizzando Deepl che per certi versi risulta veramente eccezzionale.
* UABE
* Python


### Installazione 

La patch è scaricabile al seguente link:
<!-- https://www.animecast.net/download/lang_ita_cult_of_the_lamb-v0.2016.zip -->

L'attuale versione supportata del gioco è la **v1.011**


1. Recatevi nella cartella del gioco (Nella libreria: **Tasto destro** su **Cult of the Lamb**, poi **Gestisci** ed infine **Sfoglia i file locali**
2. Entrate nella cartella Cult Of The Lamb_Data ed estraete li l'eseguibile contenuto nello zip
3. Lanciatelo e seguite la procedura guidata (teoricamente non dovreste modificare nulla e premere solo su Next)
4. Il file resources.assets verrà patchato e il Cinese semplificato verrà usato come linguaggio di appoggio, inoltre viene creato un file resources.assets.bak0000 da utilizzare (cancellando resources.assets e rimuovendo da questo file l'estensione .bak0000) per tornare alla versione normale del gioco.
5. Avviate il gioco e nelle impostazioni troverete la lingua Italana


Inutile dirvi che se il gioco dovesse subire aggiornamenti il file resources.assets ritornerà da solo alla versione originale cancellando la patch. Potere provare a quel punto a riapplicarla, ma in quel caso non ve ne garantisco il funzionamento.

### I Miei Contatti

* **GitHub:     @[Nuked88](https://github.com/Nuked88)**
* **Twitter:     @[Nuked](https://twitter.com/Nuked)**
* **Telegram: @Nuked**



# Contributing to the Hacker theme

Hi there! We're thrilled that you'd like to contribute to the Hacker theme. Your help is essential for keeping it great.

the Hacker theme is an open source project supported by the efforts of an entire community and built one contribution at a time by users like you. We'd love for you to get involved. Whatever your level of skill or however much time you can give, your contribution is greatly appreciated. There are many ways to contribute, from writing tutorials or blog posts, improving the documentation, submitting bug reports and feature requests, helping other users by commenting on issues, or writing code which can be incorporated into the Hacker theme itself.

Following these guidelines helps to communicate that you respect the time of the developers managing and developing this open source project. In return, they should reciprocate that respect in addressing your issue, assessing changes, and helping you finalize your pull requests.


## Looking for support?

We'd love to help. Check out [the support guidelines](SUPPORT.md).

## How to report a bug

Think you found a bug? Please check [the list of open issues](https://github.com/pages-themes/hacker/issues) to see if your bug has already been reported. If it hasn't please [submit a new issue](https://github.com/pages-themes/hacker/issues/new).

Here are a few tips for writing *great* bug reports:

* Describe the specific problem (e.g., "widget doesn't turn clockwise" versus "getting an error")
* Include the steps to reproduce the bug, what you expected to happen, and what happened instead
* Check that you are using the latest version of the project and its dependencies
* Include what version of the project your using, as well as any relevant dependencies
* Only include one bug per issue. If you have discovered two bugs, please file two issues
* Even if you don't know how to fix the bug, including a failing test may help others track it down

**If you find a security vulnerability, do not open an issue. Please email security@github.com instead.**

## How to suggest a feature or enhancement

If you find yourself wishing for a feature that doesn't exist in the Hacker theme, you are probably not alone. There are bound to be others out there with similar needs. Many of the features that the Hacker theme has today have been added because our users saw the need.

Feature requests are welcome. But take a moment to find out whether your idea fits with the scope and goals of the project. It's up to you to make a strong case to convince the project's developers of the merits of this feature. Please provide as much detail and context as possible, including describing the problem you're trying to solve.

[Open an issue](https://github.com/pages-themes/hacker/issues/new) which describes the feature you would like to see, why you want it, how it should work, etc.



## Your first contribution

We'd love for you to contribute to the project. Unsure where to begin contributing to the Hacker theme? You can start by looking through these "good first issue" and "help wanted" issues:

* [Good first issues](https://github.com/pages-themes/hacker/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) - issues which should only require a few lines of code and a test or two
* [Help wanted issues](https://github.com/pages-themes/hacker/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22) - issues which may be a bit more involved, but are specifically seeking community contributions

*p.s. Feel free to ask for help; everyone is a beginner at first* :smiley_cat:

## How to propose changes

Here's a few general guidelines for proposing changes:

* If you are making visual changes, include a screenshot of what the affected element looks like, both before and after.
* Follow the [Jekyll style guide](https://ben.balter.com/jekyll-style-guide).
* If you are changing any user-facing functionality, please be sure to update the documentation
* Each pull request should implement **one** feature or bug fix. If you want to add or fix more than one thing, submit more than one pull request
* Do not commit changes to files that are irrelevant to your feature or bug fix
* Don't bump the version number in your pull request (it will be bumped prior to release)
* Write [a good commit message](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)

At a high level, [the process for proposing changes](https://guides.github.com/introduction/flow/) is:

1. [Fork](https://github.com/pages-themes/hacker/fork) and clone the project
2. Configure and install the dependencies: `script/bootstrap`
3. Make sure the tests pass on your machine: `script/cibuild`
4. Create a new branch: `git checkout -b my-branch-name`
5. Make your change, add tests, and make sure the tests still pass
6. Push to your fork and [submit a pull request](https://github.com/pages-themes/hacker/compare)
7. Pat your self on the back and wait for your pull request to be reviewed and merged

**Interesting in submitting your first Pull Request?** It's easy! You can learn how from this *free* series [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github)

## Bootstrapping your local development environment

`script/bootstrap`

## Running tests

`script/cibuild`

## Code of conduct

This project is governed by [the Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## Additional Resources

* [Contributing to Open Source on GitHub](https://guides.github.com/activities/contributing-to-open-source/)
* [Using Pull Requests](https://help.github.com/articles/using-pull-requests/)
* [GitHub Help](https://help.github.com)
