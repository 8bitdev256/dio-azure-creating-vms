# dio-azure-creating-vms
Creating VMs in Azure, provided by DIO.me

Todos os serviços -> Computação -> Máquinas Virtuais -> Criar -> Máquina virtual do Azure

Se eu crio algum recurso no Azure que ele já tem, ou seja é um recurso nativo, como o Microsoft Entra ID (antigo Active Desktop Directory), e ele fica indisponível por mais tempo do que o que a SLA define para ele, a Microsoft tem que ressarcir.

Já no caso da criação de máquina virtual, o SLA é gerado a partir da minha requisição (criação/configuração da máquina virtual), então a Microsoft não tem que me ressacir em caso de indisponibilidade.

Na criação de máquinas virtuais, há ícones de informações que oferecem resumos e/ou links da documentação para maiores informações sobre cada campo a ser configurado.

Ao realizar uma configuração, a própria página oferece uma sugestão de uma configuração melhor ou recomendada (caso necessário), para lhe ajudar.

As configurações que você realiza ao criar uma VM podem impactar na disponibilidade. Portanto, siga as instruções recomendadas e caso tenha dúvidas de qual será a disponibilidade final com as configurações escolhidas, consulte a documentação.

Todos os serviços -> Contas de Armazenamento -> aba Básico

Na opção Redundância, é possível verificar diferentes opções de redundância de acordo com suas necessidades. Nas próprias opções há seus cenários recomendados.

Quanto maior a replicação, maior a disponibilidade. Portanto, essa configuração influencia na alta disponibilidade, assim como na velocidade da aplicação, na SLA, no custo, entre outros.

Antes de efetuar todas as configurações informadas anteriormente, é necessário definir primeiro a finalidade da criação destes recursos, se é para teste, se é ambiente de produção, para que o orçamento seja passado corretamente ao cliente e não haja gastos desnecessários ou configurações que não atendam a necessidade do cliente.
