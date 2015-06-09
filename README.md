# Python Parsing Tools
A list of Python parsing tools initially imported from [@nedbat's](https://github.com/nedbat) [blog post](http://nedbatchelder.com/text/python-parsers.html).

## The List

|Name|Description|License|Updated|Parses|Used By|Notes|
|:--:|-----------|:-----:|-------|------|-------|-----|
|[Ply](http://www.dabeaz.com/ply/)|Docstrings are used to associate lexer or parser rules with actions. The lexer uses Python regular expressions.|LGPL|v3.6 4/2015|LALR(1)|[lesscpy](https://github.com/lesscpy/lesscpy)|[ply-hack group](http://groups.google.com/group/ply-hack)|
|[pyparsing](http://pyparsing.wikispaces.com/)|Direct parser objects in python, built to parallel the grammar.|MIT|v2.0.3 8/2014||[twill](http://twill.idyll.org/)||
|[ANTLR](http://www.antlr.org/)|Parser and lexical analyzer generator in Java. Generates parsing code in Python (as well as Java, C++, C#, Ruby, etc).|BSD|v4.4 7/2014|LL(*)|||
|[pyPEG](http://fdik.org/pyPEG/)|A parsing expression grammar toolkit for Python.|GPL|v 2.15 1/2015|PEG|||
|[pydsl](http://pydsl.org/)|A language workbench written in Python.|GPLv3|v 0.5.2 11/2014|||
|[LEPL](http://www.acooke.org/lepl/)|A recursive descent parser.|dual licensed MPL/LGPL |v 5.1.3 9/2012||| Discontinued|
|[Codetalker](https://github.com/jaredly/codetalker)|Python-based grammar definitions.|MIT| v 1.1 3/2014||||
|[funcparserlib](https://github.com/vlasovskikh/funcparserlib)|Recurisve descent parsing library for Python based on functional combinators.|MIT| v0.3.6 5/2013||||
|[picoparse](https://github.com/brehaut/picoparse/)|v0.9 3/2009||||
|[Aperiot](https://sites.google.com/site/aperiotparsergenerator/)|Apache 2.0|v0.1.12 1/2012||||
|[PyGgy](https://pypi.python.org/pypi/pyggy/0.3)|Lexes with DFA from a specification in a .pyl file. Parses GLR grammars from a specification in a .pyg file. Rules in both files have Python action code. Unlike most parser generators, the rule actions are all executed in a post-processing step. The parser isn't represented as a discrete object, but as globals in a module.|Public Domain|v0.4 8/2004|||[Python 3 compatible fork 0.4.1](https://github.com/sprymix/pyggy), [discussion group](https://groups.google.com/forum/#!forum/pyggy)|
|[Parsing](http://www.canonware.com/Parsing/)|LR(1) parser generator as well as CFSM and GLR parser drivers.|MIT|v1.4 12/2012|LR(1), CFSM, and GLR|||
|[Rparse](https://sites.google.com/site/della1rv/therparseparsergenerator)||GPL|v 1.1.0. 4/2010|LL(1) parser generator with AST generation.|||
|[SableCC](http://sablecc.org/)|Java-based parser and lexical analyzer generator. Generates parsing code in Java, with [alternative generators](http://www.mare.ee/indrek/sablecc/) for other languages including Python.|LGPL|v 3.7 11/2012||||
|[GOLD Parser](http://goldparser.org/)||[zlib/libpng](http://opensource.org/licenses/zlib-license.html)|v 5.2.0 8/2012|LALR|||
|[Plex](https://pypi.python.org/pypi/plex/)|Python module for constructing lexical analysers.|LGPL|v 2.0 12/2009||compiles all of the regular expressions into a single DFA.|
|[Plex3](https://github.com/uogbuji/plex3)|Python3 port of Plex||8/2012|||No official release|
|[yeanpypa](http://freecode.com/projects/yeanpypa/)|Yeanpypa is (yet another) framework to create recursive-descent parsers in Python.|Public Domain|4/2010|||Parsers are created by writing an EBNF-like grammar as Python expressions.|
|[ZestyParser](https://pypi.python.org/pypi/ZestyParser)|MIT|v 0.8.1 4/2007||||
|[BisonGen](http://copia.posthaven.com/of-bisongen)||v 0.8.0b1 4/2005||||
|[DParser for Python](http://dparser.sourceforge.net/)|A scannerless GLR parser|BSD|v 1.3.0 3/2013|||[Charming Python: DParser for Python: Exploring Another Python Parser](http://gnosis.cx/publish/programming/charming_python_b19.txt)|
|[Yapps](http://theory.stanford.edu/~amitp/yapps/)|Produces recursive-descent parsers, as a human would write. Designed to be easy to use rather than powerful or fast. Better suited for small parsing tasks like email addresses, simple configuration scripts, etc.|MIT|v 2.1.1 8/2003||||
|[PyBison](http://freenet.mcnabhosting.com/python/pybison/)|Python binding to the Bison (yacc) and Flex (lex) parser-generator utilities|GPL|v 0.1.8 6/2004|LALR(1)||Doesn't yet support Windows.|
|[Yappy](http://www.dcc.fc.up.pt/~rvr/naulas/Yappy/index.html)|||v 1.9.4 8/2014|SLR, LR(1) and LALR(1)||Uses python strings to declare the grammar.|
|[Toy Parser Generator](http://cdsoft.fr/tpg/)||LGPL|v 3.2.2 12/2013||||
|[kwParsing](http://gadfly.sourceforge.net/kwParsing.html)|An experimental parser generator implemented in Python which generates parsers implemented in Python.|Python License|v 1.3|SLR|[Gadfly](http://gadfly.sourceforge.net/)|
|[Martel](http://www.dalkescientific.com/Martel/)|Martel uses regular expression format definition to generate a parser for flat- and semi-structured files.  The parse tree information is passed back to the caller using XML SAX events.  In other words, Martel lets you parse flat files as if they are in XML.|BSD|v 0.8 12/2001||[BioPython](http://biopython.org/) [versions 1.4-1.48](https://github.com/biopython/biopython/blob/6f9e7a741fdc4598509292d911020995ba2a5241/DEPRECATED#L283-L287)|[Last version included in BioPython](https://github.com/biopython/biopython/tree/29aa4df3480cdee803694766f137ab2baf5625b2/Martel)|
|[SimpleParse](http://simpleparse.sourceforge.net/)|Lexing and parsing in one step, but only deterministic grammars.|BSD|2.11a2 8/2010||||
|[mxTextTools]()|An unusual table-based parser. There is no generation step, the parser is hand-coded using primitives provided by the package. The parser is implemented in C for speed. (just above).|eGenix Public License, similar to Python, compatible with GPL.|v 3.2.8 7/2014||SimpleParse, Martel||
|[SPARK](http://pages.cpsc.ucalgary.ca/~aycock/spark/)|Uses docstrings to associate productions with actions. Unlike other tools, also includes semantic analysis and code generation phases.|MIT|v 0.7 pre-alpha 7 5/2002||||
|[FlexModule and BisonModule](http://www.crsr.net/Software/FBModule.html)|Macros to allow Flex and Bison to produce idiomatic lexers and parsers for Python. The generated lexers and parsers are in C, compiled into loadable modules. |Pythonesque|v 2.1 3/2002||||
|[Bison in a box](http://hyperreal.org/~est/freeware/)|Uses standard Bison to generate pure Python parsers. It actually reads the bison-generated .c file and generates Python code.|GPL|v 0.1.0 6/2001|LALR(1)|||
|[Berkeley YACC](http://invisible-island.net/byacc/byacc.html)|Classic YACC, extended to generate Python code. Python support seems to be undocumented.|Public Domain|v 20141128 11/2014|LALR(1)|||
|[PyLR](https://web.archive.org/web/20050728024331/http://starship.python.net/crew/scott/PyLR.html)|Lexer is based on regular expressions.||12/1997|LR|||
|[PyLR](https://github.com/Mappy/PyLR)|PyLR is a partial Python implementation of the [OpenLR specification](http://www.openlr.org)|Apache 2.0|12/2014|||[announcement](http://techblog.mappy.com/PyLR,%20an%20OpenLR%20decoder%20in%20python.html)|

## Standard Modules

The Python standard library includes a few modules for special-purpose parsing problems. These are not general-purpose parsers, but don't overlook them. If your need overlaps with their capabilities, they're perfect:

* [shlex](https://docs.python.org/2/library/shlex.html) lexes command lines using the rules common to many operating system shells.
* [ConfigParser](https://docs.python.org/2/library/configparser.html) implements a basic configuration file parser language which provides a structure similar to what you would find on Microsoft Windows INI files.
* [ArgParse](https://docs.python.org/2/library/argparse.html) The argparse module makes it easy to write user-friendly command-line interfaces. The program defines what arguments it requires, and argparse will figure out how to parse those out of sys.argv. The argparse module also automatically generates help and usage messages and issues errors when users give the program invalid arguments.
* [email](https://docs.python.org/2/library/email.html) provides many services, including parsing email and other RFC-822 structures.
parser parses Python source text.
* [cmd](https://docs.python.org/2/library/cmd.html) implements a simple command interface, prompting for and parsing out command names, then dispatching to your handler methods.

## Articles

* [http://effbot.org/zone/simple-top-down-parsing.htm](http://effbot.org/zone/simple-top-down-parsing.htm) - A methodology for writing top-down parsers in Python. (7/2008)
* [Pysec: Monadic Combinatoric Parsing in Python](http://www.valuedlessons.com/2008/02/pysec-monadic-combinatoric-parsing-in.html) - An exposition of using monads to build a Python parser. (2/2008)
