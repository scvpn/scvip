# `Install Script DANS VPN STORE`

<pre><code>apt update -y && apt upgrade -y && apt dist-upgrade -y wget -q https://raw.githubusercontent.com/Scvpn/scvip/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh</pre></code>

# `FixSSH`
<pre><code>wget -q -O fix "https://raw.githubusercontent.com/xsm-syn/fix/main/ws-700.sh" && bash fix</pre></code>

# `Manual Update`
<pre><code>wget https://raw.githubusercontent.com/Scvpn/scvip/main/updatemenu.sh && chmod +x updatemenu.sh && ./updatemenu.sh</pre></code>

# `Update Backup`
<pre><code>wget https://raw.githubusercontent.com/Scvpn/scvip/main/backup/set-br.sh && chmod +x set-br.sh && ./set-br.sh
