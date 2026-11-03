# TerribleYes  

This is the TerribleYes utility, a less-optimized version of the already existing `yes` command in most GNU/Linux installations.  
Unlike the `yes` command, designed in C, the TerribleYes utility is writted in `bash`. Utilizing a `while true` loop forces `bash` to echo all the time, which is a waste of system resources.  

# Usage

Clone this repository into ~/  
`cd ~/`  
`git clone https://github.com/elbai-codes/TerribleYes`  
Move into ~/TerribleYes  
`cd ~/TerribleYes`  
Give executable permissions to the script  
`chmod +x ./terribleyes.sh`  
Then, run the script and pipe it into any command!  
`./terribleyes.sh | command`  

# License

This code is licensed under the Do What The Fuck You Want Public License (WTFPL). Its terms can be seen [here](LICENSE)
