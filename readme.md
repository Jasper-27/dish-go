# DISH - DIscordSHell
## Shell or command and control? 
So this project is an interesting one. It started off as a fun way to control my PC through Discord. Like I could make the PC say "boobies" from across the room, without having to set up SSH. Then I realised, damn, this is a security nightmare. Then I realised DAMN this is a security nightmare. So it kind of became a command and control concept. I haven't really checked, but this feels like the kind of thing that is done to death, so nothing exciting. 

## Should i use this or the python version? 
This one can be compiled. Which is pretty useful if the target machine isn't going to be able to install all the dependencies requred. But it's important to remember that most operating systems don't like running unsigned binarys. So maybe the python version is better. 

## Setting it up
You are going to need to have Golang on the machine. Run `go run dish.go` to just run the script without compiling. You can compile with `go build dish.go`, this will build an executable, an un-signed executable. So you will need to sort that out before putting it on the target machine.

## Oooh, I could use this for illegal shit. 
Yes probably. Please don't though. 

## What operating systems has this been tested with
- MacOs (This is what i am using to build most of it)
- Windows 
- Ubuntu (will probably be compatible with most distros)

