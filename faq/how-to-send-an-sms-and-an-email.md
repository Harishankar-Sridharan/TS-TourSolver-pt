# 11. Como enviar um SMS e um Email?

* **Garanta que os dados de contato do cliente estejam disponíveis**
  * Para emails: o cliente deve ter um **Endereço de email**.
  * Para SMS: os clientes devem fornecer um **número de telefone móvel** para garantir comunicação adequada e atualizações de serviço. Para melhores resultados, insira o número em **formato internacional** (incluindo o código do país), pois isso melhora a compatibilidade e garante que o sistema consiga identificar e contatar corretamente o cliente independentemente da localização.
* **Configurar modelos de Email**\
  Ir para **Configuração → Emails de saída** e personalizar:
  * Endereço de Email do Remetente
  * Assunto
  * Conteúdo da mensagem (texto estático + campos dinâmicos) - **Janela de tempo para comunicação, Próximas Visitas, Chegada próxima, Fim da visita e Cancelamento de visita.**&#x20;
  * Links (link ETA, link de feedback, etc.)
* **Configurar modelos de SMS**\
  Ir para **Configuração → SMS de saída** e personalizar:
  * Nome do Remetente
  * Assunto
  * Conteúdo da mensagem (texto estático + campos dinâmicos) - **Janela de tempo para comunicação, Próximas Visitas, Chegada próxima, Fim da visita e Cancelamento de visita.**&#x20;
  * Links (link ETA, link de feedback, etc.)
* **Configure seus modelos de notificação**\
  Navegar para _**Configuração → Páginas de Experiência do Cliente**_ e configure as URLs que são usadas dentro dos modelos de Email ou SMS. &#x20;
* **Link da Janela de Tempo de Entrega** Fornece ao cliente a **janela de tempo de entrega agendada**. Ao clicar neste link, o cliente pode ver os horários de início e término esperados para seu intervalo de entrega.
* **Link de Rastreamento de Entrega (ETA)** Permite ao cliente **rastrear a entrega em tempo real**. Este link mostra o **tempo estimado de chegada (ETA)** e atualiza dinamicamente à medida que a rota progride.
* **Link de Fim de Entrega** Confirma que a entrega foi **concluída com sucesso**. Os clientes podem usar este link para ver os detalhes finais da entrega, como horário de conclusão e status.
* **Link de Reagendamento** Permite ao cliente **reagendar sua entrega**. Ao clicar neste link, ele pode selecionar uma nova janela de tempo ou data que melhor se adapte à sua disponibilidade.
* **Enviar notificações**\
  Quando rotas são publicadas ou quando eventos específicos ocorrem (como **comunicação de janela de tempo, notificações de chegada ou atualizações de fim de visita**), o **alternador de notificação deve ser ativado.** Uma vez ativado, o TourSolver envia o **SMS ou email configurado** ao cliente, garantindo que ele receba atualizações oportunas sobre o status da entrega ou da visita.
* **Verificar o status da entrega**
  * Use **Lista de emails enviados** para ver o status de entrega dos emails.
  * Use **Lista de SMS enviados** para verificar a entrega e o consumo de SMS.
