Common Idioms for Reading File Data
Read an entire file all at once as a string.

with open('foo.txt', 'rt') as file:
    data = file.read()
    # `data` is a string with all the text in `foo.txt`
Read a file line-by-line by iterating.

with open(filename, 'rt') as file:
    for line in file:
        # Process the line
Common Idioms for Writing to a File
Write string data.

with open('outfile', 'wt') as out:
    out.write('Hello World\n')
    ...
Redirect the print function.

with open('outfile', 'wt') as out:
    print('Hello World', file=out)
