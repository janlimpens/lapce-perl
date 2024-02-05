# lapce-perl

Lapce plugin for Perl.

## Prerequisites

Install [Perl::LanguageServer](https://metacpan.org/pod/Perl::LanguageServer),
typically by running:

```sh
cpm Perl::LanguageServer
```

## Settings

### Settings: perl_languageserver.server path

By default, the Intelephense server path is `pls`. To ensure where Intelephense is
actually installed, you can run in a terminal:

```sh
$ whereis pls
