Funcionalidades Principais:


📊 Monitoramento de Logs do Sistema
Análise do syslog para registros gerais do sistema

Monitoramento do auth.log para segurança e autenticação

Filtragem inteligente com expressões regulares (grep) para detectar:

Falhas do sistema (failed, error)

Problemas de segurança (denied, unauthorized)

Erros de autenticação e autorização

🌐 Verificação de Conectividade de Rede
Teste de conectividade com a internet usando ping

Verificação de disponibilidade de sites específicos com curl

Monitoramento de HTTP status codes para serviços web

💾 Monitoramento de Hardware
Uso de Disco: Análise com df e du para monitorar espaço em disco

Memória RAM: Verificação de uso de memória com free

CPU: Monitoramento de utilização de processamento com top

I/O: Análise de atividades de disco com iostat

⚙️ Automação com Systemd
Configuração de serviços e timers para execução automática

Agendamento de execuções periódicas

Logs de execução através do journal do systemd

Tecnologias Utilizadas:
Shell Script (Bash)

Expressões Regulares (grep)

Processamento de Texto (awk)

Systemd para agendamento e serviços

Ferramentas Linux nativas: ping, curl, df, du, free, top, iostat

Casos de Uso:
Monitoramento proativo de servidores Linux

Detecção antecipada de falhas e problemas de segurança

Auditoria de sistemas e investigação de incidentes

Otimização de recursos de infraestrutura

Relatórios automáticos de saúde do sistema

Estrutura do Projeto:
