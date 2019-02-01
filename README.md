# FlashMemory

### GRUB-IMAGE
<pre>
1. images/
2. convert image.jpg image.png
3. mv image.png desktop-grub.png
4. sudo cp desktop-grub.png /usr/share/images/desktop-base/
5. update-grub
</pre>

### LOCATE
<pre>
1. sudo updatedb
</pre>

### Javac instação NETBEANS
<pre>
sudo find / -type f -iname javac
ex: /home/legend/.local/share/Trash/files/jdk1.8.0_202/bin/javac
caminho: /home/legend/.local/share/Trash/files/jdk1.8.0_202
</pre>

### METASPLOIT ERROR PORT 5432
<pre>
#iniciar postgree
service postgresql restart
#verifique que porta esta trabalhando
ss -ant
#iniciando init
msfdb init
#armitage com cnexão
sudo msfstart-armitage
#edição da porta
sudo pluma /etc/postgresql/11/main/postgresql.conf
#search port e change 5432
service postgresql restart
msfconsole
> db_connect
</pre>

### Ettercap
<pre>
<b>Modo shell - Error: Please select an User Interface</b>
<b>Chamada da interface - não abre - sem mensagens</b>
terminal: sudo ettercap -Tq
ctrl+c
Basta abrir o ettercap
</pre>
