## xiny - Learn X in Y Minutes CLI tool

[Learn X in Y minutes](https://learnxinyminutes.com/) is a nice resource for reference or introduction to many languages. It helps to quickly grasp syntax of language and how it behaves. Inspired by `man` utility and [cheat.sh](http://cheat.sh/) I created small bash script which fetches example code from the website right into your terminal.

### Usage
It's pretty straightforward:

```bash
# download script
curl -O https://raw.githubusercontent.com/arsenlosenko/xiny/master/xiny

# you can use plain old bash
bash xiny python

# or make this file executable:
chmod +x xiny
./xiny python

# and go even further, by creating an alias, so it could be called from anywhere easily:
alias xiny="$PWD/xiny"

# and use it
xiny python
```
