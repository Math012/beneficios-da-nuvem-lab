# beneficios-da-nuvem-lab

### Alta disponibilidade
- A Microsoft aplica o SLA(Service Level Agreement).
  
- A Microsoft trabalha com base em porcentagens, sendo elas: 99%, 99,9% e 99,95% e com base nessas porcentagens. A Microsoft consegue dizer por quanto tempo(horas,dias,semanas, meses) aquele serviço em especifico estará indisponivel e todo esse processo esta de acordo do nivel de serviço. E quando aquele serviço não é entregue dentro do tempo esperado definido no acordo de nivel, a Microsoft te gera creditos relacionados ao valor daquele serviço em especifico.
  
- Quando o serviço está fora, é chamado de degradado.
  
- Todas as normas do SLA se aplica a todos os usuários.
  
### Escalabilidade e Elasticidade
- Escalabilidade é a capacidade de ajustar recursos para atender a demanda e conseguir adicionar mais recursos para lidar com o aumento da demanda.
  - Paga somente pelos recursos usados.
  - Se a demanda do serviço cair, podemos reduzir os recursos para reduzir os custos.
  - Exemplo de escala vertical: "Se um aplicativo precisasse de mais processamento, poderia escalar verticalmente para adicionar mais CPUs ou RAM à máquina virtual".
    
- Elasticidade, se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos(automaticamente ou manualmente) como, por exemplo, na black friday.
    - Você pode expandir seu ambiente conforme as requisições. Por exemplo, ao subir um servidor com uma GPU você pode colocar um limite para outro recurso ser adicionado, se a GPU passar de 75% outra será alocada para o servidor. E caso a demanda seja reduzida os recursos serão reduzidos também, manualmente ou automática. Podendo definir o máximo de recursos e o mínimo que serão alocados após a alta demanda ou baixa demanda.

 ### Confiabilidade, Previsibilidade e Segurança
 - Confiabilidade é uma etapa resiliente que apesar das falhas o sistema consegue se recuperar e continua a funcionar.
     - A nuvem trabalha com uma arquitetura descentralizada, assim sendo possível criar e implantar recursos em várias regiões do mundo.
     - Caso aconteça um evento catastrófico em uma região, as outras regiões ainda estarão em funcionamento.
       
- Previsibilidade
    - A previsibilidade na nuvem permite que você avance com confiança, seja no desempenho ou no custo. Ambas são influenciadas pelo Microsoft Azure Well Architected Framework.
    - Prestar todo o suporte para os clientes.
      
- Segurança
    -  A nuvem oferece ferramentas de segurança que atendem as necessidades dos clientes, mas, é importante lembrar que a implementação de muitas delas devem ser realizadas pelo cliente.
    -  A implementação não é responsabilidade da Microsoft. Como, por exemplo, a atualização da máquina.
