# analysis-of-dynamics
analysis of the dynamics of delinquency

**Анализ динамики просрочки**

> Задача<br>

Проанализируйте характер поведения клиентов с точки зрения просрочки: какая динамика просрочки, наблюдается ли рост или снижение?<br><br>

> Данные<br>

**orders** <br>
`order_id` – номер заявки <br>
`created_at` - дата создания заявки  <br>
`put_at` - дата выдачи <br>
`closed_at` - дата закрытия <br>
`issued_sum` - сумма выдачи <br><br>
**payments** <br>
`order_id` – номер заявки <br>
`paid_at` - дата фактического платежа <br>
`paid_sum` - сумма фактического платежа <br><br>
**plan** <br>
`order_id` – номер заявки <br>
`plan_at` – дата планового платежа <br>
`plan_sum_total` - сумма планового платежа (накопленным итогом) <br>
