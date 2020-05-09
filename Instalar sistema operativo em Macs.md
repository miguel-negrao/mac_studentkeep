# Instalar sistema operativo em Macs de raiz, limpando conteúdo anterior do disco.

1. Parte-se do pressuposto que o objetivo é apagar todo o conteúdo do disco do mac e instalar tudo de novo.
2. Arrancar o mac e usar `system_profiler` para ver o modelo do mac, p.ex. `iMac8,1`.
3. Ver em https://everymac.com qual a última versão do sistema operativo compatível com o mac.
4. Caso o mac tenha "internet recovery" (ver lista [aqui](https://www.idownloadblog.com/2016/02/25/how-to-start-up-your-mac-in-internet-recovery-mode/), desde 2010-2011), é possível instalar o sistema a partir da internet da seguinte forma.
   1. Arrancar o mac.
   2. Carregar em **Command (⌘)-R** quando o se ouve o som de arranque.
   3. Escolher rede.
   4. Instalar o sistema apagando todo o conteúdo do disco.
   5. Ver instruções [aqui](https://support.apple.com/pt-pt/HT201314). Ver como apagar o disco [aqui](https://support.apple.com/pt-pt/HT208496).
5. Caso  não se possa usar "internet recovery" (mac demasiado antigo) poderá criar-se uma uma pen que instala o sistema operativo. Provavelmente para esses macs a versão mais recente que se pode instalar é o El Captian (mas deve-se confirmar para o Mac específico).
   1. É necessário ter uma Mac funcional disponível.
   2. Nesse Mac, ir buscar o instalador da última versão compatível com o computador onde se pretende instalar. No caso do El Capitan seguir as instruções [aqui](https://support.apple.com/pt-pt/HT206886) (passo 4 Descarregar o OSX El Capitan).
   3. Criar uma pen com instalador seguindo as instruções [aqui](https://support.apple.com/pt-pt/HT201372).
   4. Depois de criar a pen, arrancar da pen carregando  em **Alt** quando o se ouve o som de arranque.
   5. No menu do instalador abrir o disk utility e apagar o disco do computador.
   6. Instalar o macos no disco limpo.