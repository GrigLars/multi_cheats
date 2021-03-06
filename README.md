# How do do common stuff in multiple languages
This is my cheatsheet for "How to" do a variety things I frequently do in various programming languages.  I will have it in a cut-n-paste version so I make less mistakes.  The order may not be the best.

- bash
- python
- perl
- golang (go)
- ansible
- ruby 
- php
- javascript
- elm
- awk

## Variable types (their names)
### Single variable types
In bash, they are not well defined, which can cause some traps in string comparisons, which are dependent on whether to operators are in quotes, have spaces, single brackets, double bracks, or parathesis.
- https://www.tldp.org/LDP/abs/html/testconstructs.html#DBLBRACKETS
- https://www.tldp.org/LDP/abs/html/dblparens.html

### Key/value types
In bash version 4 "associative arrays" were introduced.

    declare -A US_CAPITALS
    US_CAPITALS["Arizona"]="Phoenix"
    US_CAPITALS+=( ["Louisiana"]="Baton Rouge" ["Texas"]="Austin" )


In python, they are called "dictionaries"  
https://www.pythonforbeginners.com/dictionary/how-to-use-dictionaries-in-python/

In perl, they are called "hashes"  
https://perlmaven.com/perl-hashes
 
In go, they are called "maps"  
https://gobyexample.com/maps

Since ansible has its roots in python, they are also called "dictionaries"  
https://docs.ansible.com/ansible/latest/reference_appendices/YAMLSyntax.html

In ruby, they are also called "hashes"  
https://ruby-doc.org/core-2.2.0/Hash.html

To confuse the hell out of you, in php, they are called "arrays"  
http://php.net/manual/en/language.types.array.php

In javascript, it's a form of an object  
https://javascript.info/object

In elm, it's also "dictionaries"  
https://dennisreimann.de/articles/elm-data-structures-list-array-set-dict.html

awk... hm...  
https://stackoverflow.com/questions/39666084/key-value-pairs-in-awk


### Arrays
### Boolean
### Others

## For each loops

## For each key/value

bash 4.0 and above:

    for key in ${!US_CAPITALS[@]}; do
            echo " The capital of ${key} is ${US_CAPITALS[${key}]}"
        done


## If/then/else

## Case

## Open file, read

## Open file, write

