## vim

- <https://github.com/chriskempson/base16-vim/blob/master/colors/base16-default-light.vim> `c1c3e6c`
- <https://github.com/chriskempson/base16-vim/blob/master/colors/base16-default-dark.vim> `c1c3e6c`

```
3,10d | 4d | 5d | 36d | 42,49d |
4s#.*/#execute "silent !/bin/sh $HOME/.nightshell/# |
4s/\.sh// |
%s/base16-default/forgotten/ |

%s/181818/191c1f/ |
%s/282828/282c30/ |
%s/383838/444b52/ |
%s/585858/5d6770/ |
%s/b8b8b8/7f8c99/ |
%s/d8d8d8/a8b4bf/ |
%s/e8e8e8/d5dfe8/ |
%s/f8f8f8/f5faff/ |

%s/ab4642/bf3f4a/ |
%s/dc9656/d46900/ |
%s/f7ca88/d48d00/ |
%s/a1b56c/4a8000/ |
%s/86c1b9/3e947e/ |
%s/7cafc2/3f8abf/ |
%s/ba8baf/7d6fbf/ |
%s/a16946/bf60a7/ |

%s/Character",    s:gui08, "", s:cterm08/Character",    s:gui0D, "", s:cterm0D/ |
%s/Cursor",        s:gui00, s:gui05, s:cterm00, s:cterm05/Cursor",        s:gui00, s:gui0D, s:cterm00, s:cterm0D/ |
%s/Identifier",   s:gui08, "", s:cterm08, "", "none/Identifier",   s:gui0D, "", s:cterm0D, "", "bold/ |
%s/LineNr",        s:gui03, s:gui01, s:cterm03/LineNr",        s:gui04, s:gui01, s:cterm05/ |
%s/Search",        s:gui03, s:gui0A, s:cterm03, s:cterm0A,  "", "")/Search",        s:gui00, s:gui0A, s:cterm00, s:cterm0A,  "", "")/ |
%s/statusline",    s:gui04, s:gui02, s:cterm04, s:cterm02/statusline",    s:gui00, s:gui0D, s:cterm00, s:cterm0D/ |
%s/StatusLineNC",  s:gui03, s:gui01, s:cterm03, s:cterm01/StatusLineNC",  s:gui05, s:gui01, s:cterm05, s:cterm01/ |
%s/Visual",        "", s:gui02, "", s:cterm02/Visual",        s:gui06, s:gui02, s:cterm06, s:cterm02/ |
%s/VisualNOS",     s:gui08, "", s:cterm08, "", ""/VisualNOS",     "", s:gui01, "", s:cterm01, "none"/ |
%s/WildMenu",      s:gui08, s:gui0A, s:cterm08, ""/WildMenu",      s:gui00, s:gui06, s:cterm00, s:cterm06/ |

if @% =~ 'dark' | 123s/0D/08/g | 127s/0D/08/g | 143s/0D/08/g | 151s/0D/08/g | endif |

normal =gg
```



## nightshell

- <https://raw.githubusercontent.com/chriskempson/base16-shell/master/scripts/base16-default-light.sh> `376294b`
- <https://raw.githubusercontent.com/chriskempson/base16-shell/master/scripts/base16-default-dark.sh> `376294b`

```
2,4d |

%s#18/18/18#1f/1f/1f# |
%s#28/28/28#36/36/36# |
%s#38/38/38#54/54/52# |
%s#58/58/58#75/75/73# |
%s#b8/b8/b8#94/93/91# |
%s#d8/d8/d8#ba/ba/b6# |
%s#e8/e8/e8#e0/e0/dc# |
%s#f8/f8/f8#ff/fe/fa# |
%s#ab/46/42#bf/50/50# |
%s#dc/96/56#bf/7f/3f# |
%s#f7/ca/88#ab/95/2b# |
%s#a1/b5/6c#6a/94/56# |
%s#86/c1/b9#4a/94/94# |
%s#7c/af/c2#63/87/ab# |
%s#ba/8b/af#8f/72/ab# |
%s#a1/69/46#bf/80/90# |

%s/181818/1f1f1f/ge |
%s/383838/545452/g |
%s/d8d8d8/babab6/g |
%s/f8f8f8/fffefa/ge |

call append(123,["",
"echo -ne '\\e]12;#6a9456\\a'"]) |

if @% =~ 'dark' | 125s/6a9456/bf8090/ | endif |

normal =gg
```
