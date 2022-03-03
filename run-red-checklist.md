

## red won't run

* first y--  n--  running latest version?
	* stable version is old
	* many problems have been fixed since then

> please follow the text and diagram to find a solution

* you've downloaded latest from red-lang
* or
* you've cloned or downloaded source from github.com/red/red 
*  and rebol and built the gui console

 *  which OS
	* windows has AV quarantined?
	* linux  using wine or some virtual machine
		*	installed 32bit libs?
	* mac newer versions require 64 bit so need a virtual solution
		*	see docker links

## red still won't run
	*	does red --cli work?
	*	has previous versions worked?

 * windows 7, 10 64bit,  run dxdiag and showing 11
	*	using old computer with limited gpu 
	* or dxdiag version 10 or less
	*	might be stuck running older version


```
graph TD
   A(red <br>not working) --> B{windows Anti Virus?}
   B -->|No| H()
   B -->|Yes| C{?} -->|Yes| G()
   C -->|No| D{?} -->|Yes| I()
   D -->|No| F(S)
```
 	
```
```
gitter/red/welcome or help chat for more assistance
the game of 20 questions is really no fun for anyone.
* what is your OS?
* which red did you try to run
* have you tried `red --cli`
* is your AV guaranteeing the executable
* are you able to try another computer
* for Max and linux users, red only works in 32 bit mode
* Mac users can run a docker or VM
* linux users can install 32 bit libs
* does help work in the console?

```
attempt to make a checklist of potential solutions 
if red-lang executable fails to run

markdown comment?
github horrible editor, mouse cursor out of sync with select.
doesn't render graph in preview mode? need to click render or source
which scrws up the idea of referring to the file
does github wiki also support diagrams? gist is lagged 2/22
edit offline gist/run-red-checklist.mdx c&p to & from
```
