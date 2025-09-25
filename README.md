# Criando-maquina-azure
Para criar uma máquina virtual no Azure, primeiro acessamos o portal e fazemos login com a conta gratuita criada. Em seguida, utilizamos a barra de pesquisa para localizar o serviço Máquinas Virtuais. Na página, são exibidas todas as VMs existentes na conta, mas como ainda não temos nenhuma, vamos criar a primeira.

Durante a criação, alguns campos já vêm preenchidos, mas é necessário ajustar os mais importantes. Primeiro, criamos um Grupo de Recursos para organizar os recursos relacionados. No campo de nome da máquina virtual, podemos utilizar, por exemplo, "myVM". A região define onde os recursos serão hospedados, e para este teste deixamos em West US 2. Na imagem do sistema operacional, escolhemos "Windows Server 2022 Datacenter: Azure Edition - x64 Gen2".

Depois, criamos um usuário administrador com senha e configuramos a rede virtual padrão. O portal realiza uma verificação para garantir que todas as configurações estejam corretas e, após a validação, podemos concluir a criação da máquina virtual.

Com a VM criada, ela já está pronta para conexões. Como este foi apenas um ambiente de teste, ao final do processo optei por excluir os recursos utilizados, evitando assim custos desnecessários.
