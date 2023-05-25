
Ciclo de vida
### Diferença do beforeCreate, created, beforeMount e mounted

#### beforeCreate: 
Este gancho é executado imediatamente após a instância do componente ser criada, mas antes de os dados reativos serem adicionados ao componente. Nesse ponto, o componente ainda não está totalmente configurado. Você normalmente usa esse gancho para configurar eventos personalizados, inicializar propriedades ou realizar tarefas que não dependam dos dados reativos do componente.

#### created: 
O gancho created é executado após a instância do componente ser criada e os dados reativos serem adicionados ao componente. Nesse ponto, o componente foi inicializado, mas ainda não foi montado no DOM. Você geralmente usa esse gancho para realizar lógica adicional, como fazer chamadas assíncronas para buscar dados externos ou manipular os dados iniciais do componente.

#### beforeMount: 
Este gancho é executado imediatamente antes de o componente ser montado no DOM. Nesse ponto, o modelo do componente foi compilado e está pronto para ser renderizado no DOM. Você pode usar esse gancho para realizar tarefas de pré-renderização ou manipular o estado do DOM antes que o componente seja exibido.

#### mounted: 
O gancho mounted é executado após o componente ser montado no DOM. Nesse ponto, o componente está ativo e visível para o usuário. Você normalmente usa esse gancho para interagir com o DOM, adicionar ou remover eventos, ou executar tarefas que requerem a presença do componente no DOM.