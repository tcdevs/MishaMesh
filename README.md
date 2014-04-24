# MishaMesh

A set of web development centric tools in [Less](http://lesscss.org) and Javascript for faster and completer development process. Use it as a boilerplate or companion it with your existing project.

## Less mixins framework

Most mixins in this framework are split in multiple files sorted by there functionality. Just simply use the less directive [@import](http://lesscss.org/features/#import-directives-feature) to get the mixins you will need in your own project by there according folder/file.

**Mixins naming convention**
All mixins provided here have a naming convention structure like ```#functionName-propertyname();``` Note that every mixins start with a ```#``` hash character and names are split by ```-``` slash character.

**All comment mixins** - Add this line ```@import "comments/comments.less";``` on top of your .less file.

**All web-font mixins** - Add this line ```@import "fonts/webfonts.less";``` on top of your .less file.

**All font-load mixins** - Add this line ```@import "fonts/font-load.less";``` on top of your .less file.

**All font-stacks mixins** - Add this line ```@import "fonts/font-stacks.less";``` on top of your .less file.

**All font-sizes mixins** - Add this line ```@import "fonts/font-sizes.less";``` on top of your .less file.

**All reset mixins** - Add this line ```@import "fonts/resets.less";``` on top of your .less file and use **one** of the reset mixins below.

	#reset-normalize()
	#reset-EricMeyer()
	#reset-HTML5Doctor()
	#reset-Mini()
	#reset-Minimalist1()
	#reset-Minimalist2()
	#reset-Minimalist3()
	#reset-PoorMan()
	#reset-ShaunInman()
	#reset-Simpler()
	#reset-Siolon()
	#reset-TantekCelik()
	#reset-Tripoli()
	#reset-Universal()
	#reset-Vanilla()
	#reset-YUI2()
	#reset-YUI3()
	#reset()

## Quick start

Clone the repo, `git clone git@github.com:z3bbster/MishaMesh.git`, or [download the latest release](https://github.com/z3bbster/MishaMesh/zipball/master).

## Bug tracker

Have a bug, enhancement, idea or question? Please create an issue here on GitHub!

https://github.com/z3bbster/MishaMesh/issues

## Authors

**z3bbster**

+ http://github.com/z3bbster

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request