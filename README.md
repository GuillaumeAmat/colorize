# Colorize

Standalone python script to colorize standard outputs, text files, etc.

## Usage

`colorize [OPTIONS] [KEYWORD_1 KEYWORD_2...]`

Options :
* -h, --help          Display this help
* -c, --clear-screen  Clear the screen before displaying the output
* -i, --ignore-case   Colorize without taking care of the case


## Example

`$ tail -f /var/log/httpd/error.log | colorize keyword_1 keyword_2 "[0-9]"`

`$ cat my_file.txt | colorize -ci "keyword with spaces"`
