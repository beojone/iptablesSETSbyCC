# iptablesSETSbyCC
This is a bash script to implement country blocking via iptables\
Desenvolvido por Duilio Beojone Neto

#	(PT-BR)																																										   	         
\#	Bash Script para adicionar um ipset ao iptables o qual bloqueará pais(es) especificado(s) pelo usuário

\# Melhorias a fazer:		

\# - Melhorar o sed na func criaset() para redes menores que 256 hosts															       
\# - Trabalhar também com ipv6																																			       
\# - bloquear também a rede TOR																																		         
\# - verificar se os arquivos fornecidos pela arin e afrinc ainda apresentam erros (culpa deles)\
\# - suporte à mac
                                                                                                 
#	 (EN-US)                                                                                               
\#  Bash script to add ipsets to iptables based on country code(s) provided by user

\# Things to improve:			\
\# - SED on criaset(), aiming networks smaller than 256 hosts\
\# - IPv6 support\
\# - Block Tor network exit nodes\
\# - check if arin and afrinic files still corrupted (they were reporting a crazy number of hosts on some networks)					\
\# - mac support (since I dont have a mac I think this will take some more time to go...)
\
\
\
\
"I guess that makes MINIX the most widely used computer operating system in the world, even more than Windows, Linux, or MacOS. And I didn't even know until I read a press report about it." AS Tanenbaum
