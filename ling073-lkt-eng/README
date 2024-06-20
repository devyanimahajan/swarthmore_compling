Lakota and English: `apertium-lkt-eng`
===============================================================================

This is an Apertium language pair for translating between Lakota and
English. What you can use this language package for:

* Translating between Lakota and English
* Morphological analysis of Lakota and English
* Part-of-speech tagging of Lakota and English

For information on the latter two points, see subheading "For more
information" below.

Requirements
-------------------------------------------------------------------------------

You will need the following software installed:

* autoconf
* automake
* pkg-config
* lttoolbox (>= 3.5.1)
* apertium (>= 3.6.1)
* vislcg3 (>= 1.3.1)
* hfst (>= 3.15.1)
* apertium-lkt
* apertium-eng

If this does not make any sense, we recommend you look at: apertium.org.

Compiling
-------------------------------------------------------------------------------

Given the requirements being installed, you should be able to just run:

```console
$ autoreconf -fvi
$ ./configure
$ make
# make install
```

You can use `./autogen.sh` instead of `autoreconf` and `./configure` in case you're compiling
from source. If you installed any prerequisite language packages using a
`--prefix` with `./configure`, make sure to use the same `--prefix` when running
`./configure` here.

If any of this doesn't make sense or doesn't work, see https://wiki.apertium.org/wiki/Install_language_data_by_compiling

Testing
-------------------------------------------------------------------------------

If you are in the source directory after running make, the following
commands should work:

```console
$ echo "TODO test sentence 1" | apertium -d . lkt-eng
TODO test translated sentence 1

$ echo "TODO test sentence 2" | apertium -d . eng-lkt
TODO test translated sentence 2
```

After installing somewhere in `$PATH`, you should be able to do e.g.

```console
$ echo "TODO test sentence 1" | apertium lkt-eng
TODO test translated sentence 1
```

Files and data
-------------------------------------------------------------------------------

* [`apertium-lkt-eng.lkt-eng.dix`](apertium-lkt-eng.lkt-eng.dix) - Bilingual dictionary
* [`apertium-lkt-eng.lkt-eng.rtx`](apertium-lkt-eng.lkt-eng.rtx) - Structural transfer rules for translating into English
* [`apertium-lkt-eng.eng-lkt.rtx`](apertium-lkt-eng.eng-lkt.rtx) - Structural transfer rules for translating into Lakota
* [`apertium-lkt-eng.lkt-eng.lrx`](apertium-lkt-eng.lkt-eng.lrx) - Lexical selection rules for translating into English
* [`apertium-lkt-eng.eng-lkt.lrx`](apertium-lkt-eng.eng-lkt.lrx) - Lexical selection rules for translating into Lakota
* [`modes.xml`](modes.xml) - Translation modes

For more information
-------------------------------------------------------------------------------

* https://wiki.apertium.org/wiki/Installation
* https://wiki.apertium.org/wiki/apertium-lkt-eng
* https://wiki.apertium.org/wiki/Using_an_lttoolbox_dictionary

Help and support
-------------------------------------------------------------------------------

If you need help using this language pair or data, you can contact:

* Mailing list: apertium-stuff@lists.sourceforge.net
* IRC: `#apertium` on irc.oftc.net (irc://irc.oftc.net/#apertium)

See also the file [`AUTHORS`](AUTHORS), included in this distribution.
