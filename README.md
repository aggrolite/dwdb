# dwdb

Search the DD-WRT.com router database

## Synopsis

    ./dwdb linksys e1

## Description

This script searches the DD-WRT router database, located [here](http://www.dd-wrt.com/site/support/router-database).

Each argument given to the script is joined by a space. So running `dwdb foo bar baz` will do a search for "foo bar baz".

Any results are placed into a data structure and printed to standard output.

## Author

Written by Curtis Brandt <curtis@cpan.org>

## License

Beer-ware license. See LICENSE file for details.
