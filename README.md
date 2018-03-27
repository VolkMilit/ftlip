# ftlip
[Faster Then Light] INI-inspired parser

Just a little ini-inspired parser for my little projects. Yeah, I'm bad at naming things...

#### Sample ini file

``` ini
field1 = thisthing
field2 = thisthing2
field3 = thisthing3
```

#### Sample usage

``` cpp
ftlip ini("path/to/ini/file.ini");
std::string field1 = ini.get("field1");
ini.set("field1", "new thing");
ini.append("field1", " in ini");
```
