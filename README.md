Mason Engineering - Generalist Engineer exercise
===

# Prefix Search

Your objective is to write a tool named `pfxsearch` in one of the languages
shown below. This tool will display a prompt loop for users to search words by prefix and then print
a list of all words in a given dictionary that match the provided prefix (ie. words that begin
with that prefix). The dictionary is provided via the `dict.txt` file included in this repository.

## Example

For instance, a run of the program may look like this, where `>` is the prompt:

```
./pfxsearch

> ban

ban
banana
bananas
bane
bangle
bangles
:
:

> gas

gas
gasalier
gasaliers
gasan
gasbag
gasbags
gasboat
gascheck
:
:
```

# Addon 1
If you reach this stage, add support for simple character wildcards, using the `?` character
to represent "any alphabet".

## Example

For instance, a run of this enhanced program may look like this:

```
./pfxsearch 

> b?n

ban
banana
bananas
:
:
benedict
beneficial
:
bin
binary
:
:
```

# Submission

You are to build a small program that can be run from the command line as described above.

## DOs
* Fork this repo to your own user space, make it private (now possible with free accounts
  as well), and add @scorpiodawg as an outside collaborator
* Push all changes to the `master` branch of your fork when your time is up. Do not worry
  about incomplete work -- different engineers take different lengths of time and this will
  be accounted for. We will then fork your repo and review your code.
* Use one of the following languages/tools for the exercise:
  * Golang
  * Javascript with NodeJS/TypeScript
  * C/C++
  * Python 2 or 3
  * Java
  * Kotlin
  
  If you wish to use one of the languages not in this list, please chat with your interviewer first.
* Do include a `NOTES.md` with any notes worth sharing such as build instructions, and if possible, any
  _significant_ resources used during development (StackOverflow questions, articles, sites, etc. 
  You do not need to include links to questions about language syntax, for e.g.)

## DONTs
- Don't jump right in if you have any doubts as to whether your choice of language/
  framework might not be suitable for our review (e.g. less common ones such as 
  Clojure, Fortran, Elixir, etc.). Please clarify with your interviewer first.

# Acknowledgements

* Word list adapter from https://github.com/dwyl/english-words (`words_alpha.txt`)

**All the best!**
