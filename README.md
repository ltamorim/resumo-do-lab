# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

Introdução ao ambiente Cloud:
  - AZ-900 : Introdução aos Conceitos Básicos do Microsoft Azure
  - Conhecimento Básico sobre: 
    - Conceitos do Azure
    - Principais serviços do Azure
    - Principais soluções e ferramentas de gerenciamento segurança geral e segurança de rede 
    - Governança, privacidade e recursos de conformidade e gerenciamento de custos do Azure

Conceitos Iniciais de Cloud com Azure:
  - Objetivos:
      - Definir computação em nuvem.
      - Definir modelos de nuvem, incluindo público, privado e híbrido.
      - Identificar os casos de uso apropriados para cada modelo de nuvem.
      - Descrever o modelo baseado no consumo.
      - Comparar os modelos de preços de nuvem.

- O que é a computação em nuvem? A computação em nuvem é o fornecimento de serviços de computação pela Internet, habilitando inovações mais rápidas, recursos flexíveis e economias de escala. - Fornecer serviços pela Internet, criar recursos pela Internet.
Data Center - EVirtualização de computadores e servidores, ou seja, emular em uma máquina, várias outras máquinas.

Servidor, Rede, Computação, tudo pode ficar na nuvem. - Paga somente por aquilo que usa

- Nuvem Privada: 
  - As organizações criam um ambiente em nuvem em seu datacenter.
  - As organizações são responsáveis por operar os serviços que fornecem.
  - Não fornece acesso aos usuários fora da organização.

  - Nuvem Pública:
    - Pertencente a serviços de nuvem ou provedor de hosting.
    - Fornece recursos e serviços a várias organizações e usuários.
    - Acessada via conexão de rede segura  (geralmente pela Internet).

  - Nuvem Híbrida:
    - Combina nuvens públicas e privadas para permitir que os aplicativos sejam executados no local mais adequado.
   
  - Modelo Multicloud

  Comparação de modelos de nuvem:
    Nuvem Pública:
      - Nenhuma despesa de capital para escalar verticalmente.
      - Os aplicativos podem ser provisionados e desprovisionados rapidamente.
      - As organizações pagam apenas pelo que utilizam.
    Nuvem Privada:
      - As organizações têm controle total sobre os recursos e a segurança. 
      - As organizações são responsáveis pela manutenção e pelas atualizações de hardware.
    Nuvem Híbrida:
      - As organizações determinam onde executar seus aplicativos.
      - As organizações controlam a segurança, a conformidade e os requisitos legais.
      - Fornece a maior flexibilidade.

Tipo de Consumo: CapEx e OpEx (CERTIFICAÇÃO)

  Despesas de capital (CapEx):
    - O gasto inicial de dinheiro em infraestrutura física.
    - As despesas do CapEx têm um valor que se reduz com o tempo.

  Despesas operacionais (OpEx)
    - Gastar com produtos e serviços conforme necessário, pagamento conforme o uso. 
    - Seja cobrado imediatamente.

  Modelo baseado em consumo: Os provedores de serviços em nuvem operam em um modelo baseado no consumo,  o que significa que os usuários finais pagam somente pelos recursos que usam.
  -M elhor previsão de custos.
  - São fornecidos preços para recursos e serviços individuais.
  - A cobrança é feita com base no seu uso real.


Benfícios da Nuvem 
  - Benefícios da alta disponibilidade e da escalabilidade na nuvem.
  - Benefícios da confiabilidade e da previsibilidade na nuvem.
  - Benefícios da segurança e da governança na nuvem.
  - Benefícios da capacidade de gerenciamento na nuvem.

- Alta Disponibilidade:
  - Se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer.
  - O Azure é um ambiente de nuvem altamente disponível com garantias de tempo de atividade, dependendo do serviço.
  - Essas garantias fazem parte dos SLAs  (Contratos de Nível de Serviço).

- Escalabilidade:
  - Refere-se à capacidade de ajustar recursos para atender à demanda.
  - A capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda.
  - O outro benefício da escalabilidade é que você não está pagando além do necessário pelos serviços.
  - Como a nuvem é um modelo baseado em consumo, você paga apenas pelo que usa.
  - Se a demanda cair, você poderá reduzir seus recursos e, assim, reduzir seus custos.
  Com a escala vertical, se você estivesse desenvolvendo um aplicativo e precisasse de mais capacidade de processamento, poderia escalar verticalmente para adicionar mais CPUs ou RAM à máquina virtual.

- Elasticidade:
  - Se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (automaticamente ou manualmente).
  - Por exemplo, você pode adicionar máquinas virtuais ou contêineres por meio da expansão.
  - Da mesma forma, se houver uma queda significativa na demanda, os recursos implantados poderão ser reduzidos horizontalmente.
 
-  Confiabilidade:
  - Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente.
  - Com um design descentralizado, a nuvem permite que você tenha recursos implantados em várias regiões do mundo.
   - Com essa escala global, mesmo que ocorra um evento catastrófico em uma região, as outras regiões ainda estarão em funcionamento. 

- Previsibilidade:
  - Permite que você avance com confiança, seja no desempenho ou no custo. Ambas são influenciadas pelo Microsoft Azure Well-Architected Framework.

- Segurança:
  - A nuvem oferece ferramentas de segurança que atendem às necessidades dos clientes mas, é importante lembrar que a implementação de muitas delas devem ser realizadas pelo cliente.
  - Se você quiser o controle máximo da segurança, a infraestrutura como serviço fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutenção.
  - Se você quiser que a aplicação de patches e a manutenção sejam tratadas automaticamente, as implantações de plataforma como serviço ou software como serviço podem ser as melhores estratégias de nuvem para você.

- Governança:
  - A auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação. 
  - Dependendo do seu modelo operacional, patches de software e atualizações também podem ser aplicados automaticamente, o que ajuda na governança e na segurança.
  - Ao estabelecer uma presença de governança o mais cedo possível, você poderá manter sua presença de nuvem atualizada, protegida e bem gerenciada.

-  Gerenciabilidade:
  - Um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento. Há dois tipos de capacidade de gerenciamento para computação em nuvem que você aprenderá nesta série e ambos trazem excelentes benefícios.
  - O gerenciamento da nuvem diz respeito a gerenciar seus recursos de nuvem. Por exemplo:
    - Escalar automaticamente a implantação de recursos com base na necessidade.
    - Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.
  - O gerenciamento na nuvem diz respeito à maneira de gerenciar seu ambiente de nuvem e seus recursos. Por exemplo:
    - Por meio de um portal da Web.
    - Usando uma interface de linha de comando.
    - Usando APIs.
    - Usando o PowerShell.









































