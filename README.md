# ftlip
[Faster Then Light] INI-inspired parser

Just a little ini-inspired parser for my little projects. Yeah, I'm bad at naming things...

#### What this project never will be doing

- Parse sections, this is ini-inspired parser, not ini parser

#### Sample ini file

``` ini
field1 = thisthing
field2 = thisthing2
field3 = thisthing3
#this is commentary
#field4 = blabla this is also commentary
```

#### Sample usage

``` cpp
ftlip ini("path/to/ini/file.ini");
std::string field1 = ini.get("field1");
ini.set("field1", "new thing");
ini.append("field1", " in ini");
```

#### Know bugs

- Commented fileds can be overwriten by 'set' or 'append' methods.
