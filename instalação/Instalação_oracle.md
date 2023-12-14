# Como criar um servidor de Banco de dados Oracle

### Será necessário instalar algumas coisas:

    - [Oracle Linux 7.9](https://edelivery.oracle.com/osdc/faces/SoftwareDelivery)
    - [Oracle VirtualBox](https://www.virtualbox.org/wiki/Downloads)
    - [MobaXTerm (Caso eseteja utulizando Windows)](https://mobaxterm.mobatek.net/download.html)
    - [ZIP dos binários do Oracle Database](https://www.oracle.com/br/database/technologies/oracle19c-linux-downloads.html)

# Futuramente adicionar prints dos sites aqui


### Após as instalações podemos abrir o **Virtual Box** e criar uma nova Máquina Virtual (VM) para instalarmos o **Oracle Linux**

<img src="../assets/instalação/inicio_virtual_box.png">

Agora podemos decidir um nome para a nossa VM, eu vou utilizar o nome **oracle19c**
Tendo em vista que essa VM será responsavel por manter um servidor com o Oracle 19c instalado nela

<img src="../assets/instalação/nome_vm.png">

Agora podemos apertar em próximo para seguir para a próxima página onde vamos escolher o quanto de memória e CPU vamos utilizar na VM

A minha recomendação é de no minimo usar 1 CPU, mas o ideal acredito que seja 2 CPU
E tambem ter no minimo 2GB de memória RAM para a VM, mas o ideal é usar 4GB de memória RAM

*Saiba que quanto menos recursos sua VM possuir, mais tempo ela vai levar para realizar operações*

<img src="../assets/instalação/memoria_cpu.png">

Agora vamos definir um armazenamento de 60GB para o disco da VM

<img src="../assets/instalação/tamanho_disco_vm.png">

