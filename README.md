"# gitLearn" 
13:05 17.04.2020
выполненные команды
git init
Инициализация. Создает в локальном репозитории скрытую папку .git

Добавьте в дирректорию файл hi.txt
git status
Проверка статуса отслеживаемой папки


On branch master
No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

		hi.txt

nothing added to commit but untracked files present (use "git add" to track)

14:22 17.04.2020
===
###  Подключение к удаленному репозиторию Запушить в удаленный репозитроий
		
This is only an example. Replace the URI with your own repository address.
		$ git remote add origin git remote add origin https://github.com/instocky/gitLearn.git
		


# This is an H1
## This is an H2
###### This is an H6

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_


* Item 1
* Item 2
  * Item 2a
  * Item 2b
  
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
   

![Pic Logo](/src/logo.png)

[GitHub](http://github.com)

As Kanye West said:

> We're living the future so
> the present is our past.

### Inline code
I think you should use an
`<addr>` element here instead.

### Codes
    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
	
```js
function fancyAlert(arg) {
  if(arg) {
	$.facebox({div:'#foo'})
  }
}
```

### Task Lists
- [x] @mentions, #refs, [links](https://google.com){:target="_blank"}, **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

### Tables
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2 | test
Content in the first column | Content in the second column