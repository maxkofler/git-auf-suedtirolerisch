# Git af Südtirolerisch

Olm wieder tratzts uan wennmen mit uan iber `git` reidn muas, des denglisch isch nix, sellatwegn mochmr des iatz ordentlich.

Git hoast sou viel wia Lopp, Dummkopf, Off... Mir einign ins af `lopp`.

## Sou hoasts wirklich

Do sein zwoa listn wous richtig drausteat:

| Englisch    | Denglisch     | Südtirolerisch |
| ----------- | ------------- | -------------- |
| init        | initten       | augeats        |
| add         | adden         | zuitian        |
| blame       | blamen        | blamiern       |
| pull        | pullen        | ziachn         |
| push        | pushen        | schiabn        |
| clone       | clonen        | okupfern       |
| fetch       | fetchen       | houln          |
| branch      | branchen      | astlen         |
| commit      | commiten      | verpflichtn    |
| rebase      | rebasen       | aufrolln       |
| diff        | diffen        | schaugmrmol    |
| merge       | mergen        | zomtian        |
| fork        | forken        | gobln          |
| stash       | stashen       | housnsock      |
| tag         | taggen        | stempln        |
| cherry-pick | cherry-picken | kerstnklaubn   |
| checkout    | checkouten    | hupfn          |
| squash      | squashen      | zommdruckn     |

Do nou a poor wertlen dia ma vielleicht brauchn kannt, nit:

| Substantiv    | Aktueller Gebrauch | Vorschlag     |
| ------------- | ------------------ | ------------- |
| git           | git                | lopp          |
| github        | github             | loppnhaufn    |
| gitlab        | gitlab             | loppnlabor    |
| gitea         | gitea              | loppntee      |
| blame         | blame              | blamiern      |
| bitbucket     | bitbucket          | bitkibl       |
| repository    | repo               | misthaufn     |
| branch        | branch             | ost           |
| commit        | commit             | auschreibn    |
| log           | log                | bibel         |
| pull request  | pull request       | ziachounfrog  |
| merge request | merge request      | zomtianonfrog |
| stash         | stash              | housnsock     |
| status        | status             | wiaschaugsaus |
| tag           | tag                | stempl        |
| origin        | origin             | quell         |
| master        | master             | moastr        |
| main          | main               | schef         |

## A poor beispielelen

    - Du gea, ziach mir amol den oscht denni grod nui augrollt hon und schiabn afn loppnzentum aui.

    - Fir des honi an misthaufn autoun, nor mogsch dr lei in paschgl ost nemmen und lousleign.

    - Na des schiabmr lei frisch afn moaster in dr quell!

    - Schaugsch in dr blamierung inni, nor sigsch schun wella off den schmorrn augfiahrt hot.

    - Du i bin grod weck geostet, nor tua i mein zuig fan housnsock frisch inni verplichtn.

    - Do klaubmr om besten di kersten ausser

## Lopp hernemmen

Iatz mogsch des lei olls in deiner schelf innikearn nor konsch `lopp` benutzen wia sichs keart:

```bash
git config --global alias.augeats init
git config --global alias.okupfern clone
git config --global alias.ziachn pull
git config --global alias.zuitian add
git config --global alias.schiabn push
git config --global alias.kroftschiabn 'push --force'
git config --global alias.kroftschiabn-mit-vorbeholt 'push --force-with-lease'
git config --global alias.kroftschiabn-obr-nit-gonz-sichr 'push --force-with-lease'
git config --global alias.astl branch
git config --global alias.ost branch
git config --global alias.auschreibn commit
git config --global alias.aufrolln rebase
git config --global alias.schaugmrmol diff
git config --global alias.schaugmr diff
git config --global alias.zomtian merge
git config --global alias.insteckn stash
git config --global alias.housnsock stash
git config --global alias.stempln tag
git config --global alias.hupf checkout
git config --global alias.chronik log
git config --global alias.bibel log
git config --global alias.wiaschaugsaus status
git config --global alias.blamiern blame
```

Zlescht tuasch des nout in deiner `~/.bashrc` inni nor hosch `git` a als `lopp` zar verfügung:

```bash
alias lopp=git
```
