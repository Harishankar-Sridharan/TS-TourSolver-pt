# 13. Por que tenho tempo de espera no meu plano de rota?

O algoritmo de otimização pode introduzir tempo de espera por estas razões:

1. O entregador chega ao local do cliente **antes do horário de abertura**.
2. O entregador chega ao depósito **antes de se tornar operacional**.

Os horários de abertura do cliente e do depósito são restrições estritas com alta prioridade, portanto o algoritmo deve respeitá-los.

**Dica:** Para reduzir o tempo de espera desnecessário, use o **Tempo de Início Automático** restrição. Esse recurso ajusta o horário de partida para que o entregador comece mais tarde e chegue ao cliente ou ao depósito no momento certo, minimizando períodos ociosos em locais desconhecidos.
