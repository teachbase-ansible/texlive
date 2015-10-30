TeXLive
========

Installs TeXLive and latexmk.

Installation
--------------

`ansible-galaxy install palkan.texlive`

Role Variables
--------------

`defaults/main.yml`

| Name                        | Default Value |  Description    |
|-----------------------------|---------------|-----------------|
| latexmk_src                 | "http://mirror.physik-pool.tu-berlin.de/tex-archive/support/latexmk/latexmk.pl"        |  |
| latexmk_usr                 | None | latexmk owner

Example Playbook
-------------------------
```yml
  - hosts: servers
    roles:
       - palkan.texlive
```
