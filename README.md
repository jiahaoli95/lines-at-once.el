# lines-at-once.el
This package for Emacs allows you to quickly insert and edit multiple lines at once.

## Setup
Install the package and bind `key` to the command `lines-at-once-insert`.

## Usage
The usage is very simple. Just type a line you want to repeat as usual, with strings you want to modify replaced with `@`, and add a number to the end of the line(separated by a blank) to indicate the number of times to repeat. Then hit `key`, you get multiple lines at once, and you can hit `TAB` to quickly jump to the next position you want to modify.

See the video demo below to better understand it.

## Demo
[![Alt text](https://img.youtube.com/vi/7ZoYGpRn9w0-A/0.jpg)](https://www.youtube.com/watch?v=7ZoYGpRn9w0-A)

## Notes
* To use literal `@` in you line, use `\` to escape.
* If `TAB` conflicts with existing key bindings, you can rebind the command `lines-at-once-next` to another key sequence.