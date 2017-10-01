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
%s/585858/676c70/ |
%s/b8b8b8/8d9399/ |
%s/d8d8d8/b0b8bf/ |
%s/e8e8e8/dfe3e8/ |
%s/f8f8f8/f5faff/ |

%s/ab4642/d44652/ |
%s/dc9656/d47211/ |
%s/f7ca88/bf850f/ |
%s/a1b56c/659425/ |
%s/86c1b9/3e947e/ |
%s/7cafc2/3f8abf/ |
%s/ba8baf/7d6fbf/ |
%s/a16946/bf6fab/ |

%s/Character",    s:gui08, "", s:cterm08/Character",    s:gui0D, "", s:cterm0D/ |
%s/Cursor",        s:gui00, s:gui05, s:cterm00, s:cterm05/Cursor",        s:gui00, s:gui0D, s:cterm00, s:cterm0D/ |
%s/CursorLineNr",  s:gui04, s:gui01, s:cterm04, s:cterm01/CursorLineNr",  s:gui00, s:gui03, s:cterm00, s:cterm03/ |
%s/Identifier",   s:gui08, "", s:cterm08, "", "none/Identifier",   s:gui0D, "", s:cterm0D, "", "bold/ |
%s/LineNr",        s:gui03, s:gui01, s:cterm03/LineNr",        s:gui04, s:gui01, s:cterm05/ |
%s/MatchParen",    "", s:gui03, "", s:cterm03/MatchParen",    s:gui00, s:gui03, s:cterm00, s:cterm03/ |
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

%s#18/18/18#19/1c/1f# |
%s#28/28/28#28/2c/30# |
%s#38/38/38#44/4b/52# |
%s#58/58/58#5d/67/70# |
%s#b8/b8/b8#7f/8c/99# |
%s#d8/d8/d8#a8/b4/bf# |
%s#e8/e8/e8#d5/df/e8# |
%s#f8/f8/f8#f5/fa/ff# |
%s#ab/46/42#bf/3f/4a# |
%s#dc/96/56#d4/69/00# |
%s#f7/ca/88#d4/8d/00# |
%s#a1/b5/6c#4a/80/00# |
%s#86/c1/b9#3e/94/7e# |
%s#7c/af/c2#3f/8a/bf# |
%s#ba/8b/af#7d/6f/bf# |
%s#a1/69/46#bf/60/a7# |

%s/181818/191c1f/ge |
%s/383838/444b52/g |
%s/d8d8d8/a8b4bf/g |
%s/f8f8f8/f5faff/ge |

call append(123,["",
"echo -ne '\\e]12;#3f8abf\\a'"]) |

if @% =~ 'dark' | 125s/3f8abf/bf3f4a/ | endif
```
