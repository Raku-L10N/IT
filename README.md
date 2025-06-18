[![Actions Status](https://github.com/Raku-L10N/IT/actions/workflows/linux.yml/badge.svg)](https://github.com/Raku-L10N/IT/actions) [![Actions Status](https://github.com/Raku-L10N/IT/actions/workflows/macos.yml/badge.svg)](https://github.com/Raku-L10N/IT/actions) [![Actions Status](https://github.com/Raku-L10N/IT/actions/workflows/windows.yml/badge.svg)](https://github.com/Raku-L10N/IT/actions)

NAME
====

L10N::IT - Italian localization of Raku

SYNOPSIS
========

    $ itaku -e 'dillo "Ciao Mondo"'
    Ciao Mondo

```raku
use L10N::IT;
dillo "Ciao Mondo";
```

DESCRIPTION
===========

The `L10N::IT` distribution contains the logic to provide a Italian localization of the Raku Programming Language. It installs a `itaku` executable that will automatically activate the Italian localization. And it allows one to use the Italian localization in selected programs with a `use L10N::IT` statement.

AUTHORS
=======

JJ Merelo

COPYRIGHT AND LICENSE
=====================

Copyright 2023, 2025 Raku Localization Team

This library is free software; you can redistribute it and/or modify it under the Artistic License 2.0.

