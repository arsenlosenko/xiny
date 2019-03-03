## linym - Learn X in Y Minutes CLI tool

[Learn X in Y minutes](https://learnxinyminutes.com/) is a nice resource for reference or introduction to many languages. It helps to quickly grasp syntax of language and how it behaves. Inspired by `man` utility and [cheat.sh](http://cheat.sh/) I created small bash script which fetches example code from the website right into your terminal.

### Usage
It's pretty straightforward:

```bash
# using plain old bash
bash linym python

# or make this file executable:
chmod +x linym
./linym python

# and go even further, and create alias, so it could be called from anywhere easily:
alias linym="$PWD/linym"

linym python
```
