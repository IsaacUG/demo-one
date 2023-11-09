#Demo Git Respository

This is the first file in the repo.

##WLITTLEE MORE


##Ipsum Below

CUTTING PUBLIC KEYS
cat ~/.ssh/id_rsa.pub

LARGE FILES ON SERVER.
du -cha --max-depth=1 / | grep -E "M|G|T"

ADDING ALIAS
sudo nano ~/.bashrc

alias Alpha="ssh isaacug@34.242.206.96"
alias Omega="ssh isaacug@52.16.241.130"
alias Staging="ssh isaacug@34.244.86.180"
alias Webserver="ssh isaacug@52.209.51.245"
alias ProductionDB="ssh isaacug@108.128.84.167"
alias ReservedNDB="ssh isaacug@3.249.25.179"
alias Alpha="ssh isaacug@34.242.206.96"
alias OFS="ssh -p 10099 ubuntu@197.254.107.78"



sudo systemctl start ofs.service - Start a Service.

LOG IN TO ALPHA SERVER
AWS Logins
username: dhibikirwa
pssd: dhibikirwa@copia

Alpha Server access command. aws ssm start-session --target i-01e0f9f46c6de67c1

To switch to Odd DB
export PGPASSWORD='3rp_=dYLUw4' && pgcli -d odoo_erp -h localhost -p 6432 -U odoo
