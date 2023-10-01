# Projeto de Estudo - Análise estatística


O estudo em questão se concentrou na análise de um conjunto de dados fictício pertencente a uma empresa de telecomunicações. Durante essa análise, foram investigados apectos de diferentes planos de serviços oferecidos pela empresa, bem como caracteristicas expecificas de algumas regiões. Adicionalmente, foram identificadas diferenças significativas entre os planos disponíveis, o que permitiu uma compreensão mais profunda do comportamento dos clientes.

Para realizar essa análise, utilizei quatro conjuntos de dados principais: `df_calls`, `df_int`, `df_msg`, `df_plans` e `df_user`.

Aqui está uma breve descrição de cada um deles:

`df_calls`
- id: número de referência único para cada chamada.
- user_id: número de referência único para cada usuário.
- call_date: data da ligação.
- duration: duração da ligação.

`df_int`
- id: número de referência único para cada acesso à internet.
- user_id: número de referência único para cada usuário.
- session_date: data de acesso à internet.
- mb_used: quantidade de megabytes consumidos em cada acesso.

`df_msg`
- id: número de referência único para cada mensagem.
- user_id: número de referência único para cada usuário.
- message_date: data de envio da mensagem.

`df_plans`
- messages_included: quantidade de mensagens incluídas em cada plano.
- mb_per_month_included: quantidade de megabytes incluídos em cada plano.
- minutes_included: quantidade de minutos incluídos em cada plano.
- usd_monthly_pay: valor mensal em dólares do plano.
- usd_per_gb: preço por gigabyte adicional.
- usd_per_message: preço por mensagem adicional.
- usd_per_minute: preço por minuto adicional.
- plan_name: nome do plano.

`df_user`
- user_id: número de referência único para cada usuário.
- first_name: primeiro nome do usuário.
- last_name: sobrenome do usuário.
- age: idade do usuário.
- city: cidade onde o usuário está localizado.
- reg_date: data de registro do usuário.
- plan: plano atual do usuário.
- churn_date: data de saída (se aplicável) do usuário.


Durante a análise, conduzi dois testes de hipótese simulando cenários relevantes para uma empresa desse setor. Isso me permitiu obter insights valiosos sobre o desempenho dos diferentes planos e entender melhor o comportamento dos clientes em relação ao uso de serviços de telecomunicações.

Essa análise de dados poderia fornecer à empresa informações cruciais para tomar decisões estratégicas informadas e aprimorar seus serviços, garantindo a satisfação dos clientes e o sucesso contínuo no mercado.
