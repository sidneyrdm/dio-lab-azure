

<h1 align="center"> dio-lab-azure </h1>
<h3 align="center"> resumo de lab sobre o tema 'Configurando Recursos e Dimensionamentos em Máquinas Virtuais na AzureConfigurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure'. </h3>

### Criando uma máquina virtual   
* tipo de assinatura(por default já vem a assinatura utilizada na conta que está logada)
* grupo de recursos(pode-se utilizar algum grupo já existente ou criar um novo)
* nome da máquina virtual(você deve escolher um nome para a sua máquina que está sendo criada)
* região(ideal que se escolha a região que está mais próxima fisicamente do local ou a região que tiver um custo mais baixo, depende da sua necessidade)
* disco de SO(deixar marcado a opção"excluir com VM" para evitar custos depois que a máquina for excluída)
* escolher interface de rede(você pode escolher alguma vnet já criada anteriormente ou criar uma nova no momento da crição da máquina)
* ainda dentro do contexto de rede, você deve marcar a opção"excluir o IP público e a NIC quando a VM for excluída" para evitar custos depois que a máquina for excluída

#### opções de disponibilidade 
* zona de disponibilidade - você escolhe até 3 zonas onde será criada uma máquina em cada zona selecionada.
* Conjunto de dimensionamento - você configura e dimensiona os recursos necessários de acordo com a ideia de demanda que você tem, para que quando aumentar a demanda e chegar em um valor definido, seus recursos possam ser aumentados de forma automática e da mesma forma os recursos diminuem quando a demanda cair, você define os recursos mínimos e máximos.
* Conjunto de disponibilidade - Distribua sua VMs automaticamente entre vários domínios de falha, fazendo com que diminua a possibilidade de que seu serviço venha cair.

### Gerenciamento
* opção de desligamento automático, você pode definir o horário do desligamento e pode configurar um email para receber uma notificação antes do desligamento ocorrer.
* habilitar backup

### Monitoramento
* regras de alerta
* diagnóstico
* integridade

### Revisar + Criar
* resumo sobre todos os recursos que você definiu para sua VM e um valor de custo por hora para a máquina que está sendo criada.



