# How do do common stuff in multiple languages
This is my cheatsheet for "How to" do a variety things I frequently do in various programming languages.  I will have it in a cut-n-paste version so I make less mistakes.  The order may not be the best.

- bash
- python
- perl
- golang (go)
- ansible


## Variable types (their names)
### Single variable types
In bash, they are not well defined, which can cause some traps in string comparisons, which are dependent on wheteher to operators are in quotes, have spaces, single brackets, double bracks, or parathesis.
- https://www.tldp.org/LDP/abs/html/testconstructs.html#DBLBRACKETS
- https://www.tldp.org/LDP/abs/html/dblparens.html

### Key/value types
In bash version 4 associative arrays were introduced.

    declare -A arr
    arr["key1"]=val1
    arr+=( ["key2"]=val2 ["key3"]=val3 )

### Arrays
### Boolean
### Others

## For each loops

## For each key/value
    for key in ${!arr[@]}; do
        echo ${key} ${arr[${key}]}
    done

## If/then/else

## Case

## Open file, read

## Open file, write

