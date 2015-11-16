# Debugging
I'm just starting to learn javaScript and Ruby, an I thought that conceptualizing how I debug would be useful for me and hopefully for other people as well. Therefore...

##A flowchart for debugging your code
Obivously, this does not even begin to cover everything, but it seems like a good place to start.
![A debugging flowchart](./debugging.png)

##Tools for debugging
Find
* Use the find function in your text editor to be *very sure* that the variable you are calling has **exactly the same name** as the variable you declared.

Linters
* Linters are pretty good at catching syntax errors, so litening to what they tell you is probably a good place to start. No sense wasting time over a missing comma.

Javascript
* console.log()
* use the console to set pauses in debugger, and while paused, investigate what's going on using the console
* write `debugger;` in your code to pause in debugger

Rails
* byebug gem
* `render json: <whatever you want to see>`





