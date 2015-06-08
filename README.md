# Python Parsing Tools
A list of Python parsing tools initially imported from [@nedbat's](https://github.com/nedbat) [blog post](http://nedbatchelder.com/text/python-parsers.html).

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
|[http://effbot.org/zone/simple-top-down-parsing.htm](http://effbot.org/zone/simple-top-down-parsing.htm)|Not a tool exactly, but a methodology for writing top-down parsers in Python.|HPND|July 2008|||Blog post|
|[Pysec: Monadic Combinatoric Parsing in Python](http://www.valuedlessons.com/2008/02/pysec-monadic-combinatoric-parsing-in.html)|An exposition of using monads to build a Python parser.||2/2008|||Blog post|
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
