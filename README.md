# GDB cheat sheet

### Preface

- During my studies at 42 Porto, I used many times this wonderful tool for debugging and better understanding my projecs, however, I decided to have this repo a handy future for other students and myself not to forget how to properly take advantage of this tool!\
- I am in no way an expert, very far from that, but I decided to put up this colection of handful functionalities with my favourite notation style and functions I use the most, maybe it will be useful to you too!\
- This cheat sheet is somewhat of a collage of many cheat sheets I have read through and a few videos on the topic, I will leave my main inspiration and resources linked at the end.

## Introduction and Notation method
**Note:** this is by no means an exhaustive list of commands but more so a useful quick to parse and remember list of commands, followed by a minor breakdown of how they work. This should help programming students just like myself to quickly remind how the program works.\
Commands will have the following notation:

<table><tr><td>[c]ommand1 |required arg| (option arg)</td></tr></table>

where the brackets`[]` will be the shorthand form of the command, if the command is fully in brackets `[command2]` it means there isn't a shorthand form of the command (at least that I am aware of).\
By extension, commands that require an arg will be list with `|arg|` after the command and optional ones with `(arg)` like the aforemention example. 



## Resources and further learning
- [C246 from University of Waterloo](https://youtu.be/svG6OPyKsrw?si=dveFmxMX5QbwFoTW) (youtube video)\
╰─-> Best tutorial overall I have found online, explain in further detail and examples most of the commands in this list!
- [University of Brown GDB cheat sheet](https://cs.brown.edu/courses/cs033/docs/guides/gdb.pdf) (PDF file)\
╰─-> Lacking in completeness but easy to understand and useful notation method, my reference for notation.
- [University of Texas GDB refence sheet](https://users.ece.utexas.edu/~adnan/gdb-refcard.pdf) (PDF file)\
╰─-> Very comprehensive, harder to parse, however. Nonetheless, a good resource.
- RTF: **man gdb**, always read the friendly manual :)
