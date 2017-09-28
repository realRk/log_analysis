# log_analysis

> Rakesh R

## To Run

### You will need:
- Python3
- Vagrant
- VirtualBox

### Setup
1. Install Vagrant And VirtualBox
2. Clone this repository

### To Run

Launch Vagrant VM by using the command `vagrant up` and then  `vagrant ssh` to login

To load the data, use the command `psql -d news -f newsdata.sql` to connect a database.

The database includes three tables:
- Authors table
- Articles table
- Log table

To execute the program, run `python3 main.py` from the command line.
