# ZABBIX-Monitoring-percentage-HD-Memory-CPU

Chave de monitoramento de consumo de HD, Memória e CPU em percentual
Tested on Zabbix 4.0.x / 5.0.0 / 5.4.0 | Windows Server 2008 / 2012 / 2016 / 2019

Crie os Itens com as chaves:
#Monitoramento de consumo em percentual do HD:
key: vfs.fs.size[C:,pused]

#Monitoramento de consumo em percentual do Memória:
Key vm.memory.size[pused]

#Monitoramento de consumo em percentual do CPU:
Key: perf_counter[\Processor Information(_Total)\% Processor Utility]

Importe o template, vincule o Host e comece a monitorar!
