# This is a periodic table utility.
## Setup
- download and setup a postgresql database.
- take a dump of the periodic tables data with "psql periodic_table < periodic_table.sql"
## Usage
###Example:
./element.sh 1, ./element.sh H, or ./element.sh Hydrogen
###Output:
The element with atomic number 1 is Hydrogen (H). It's a nonmetal, with a mass of 1.008 amu. Hydrogen has a melting point of -259.1 celsius and a boiling point of -252.9 celsius.
