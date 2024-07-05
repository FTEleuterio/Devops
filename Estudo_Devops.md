<aside>
💡 ***Nexus versiona os entregáveis***
**Bread:** para versionar, homologação.
**Merge:** á versão final

**Terraform:**

</aside>

# DevOps

**DevOps** significa para as equipes? O **DevOps** permite que funções anteriormente isoladas – desenvolvimento, operações de TI, engenharia da qualidade e segurança – atuem de forma coordenada e colaborativa para gerar produtos melhores e mais confiáveis.
O DevOps permite que funções anteriormente isoladas – desenvolvimento, operações de TI, engenharia da qualidade e segurança – atuem de forma coordenada e colaborativa para gerar produtos melhores e mais confiáveis.

## **DevOps e o ciclo de vida do aplicativo**

O DevOps influencia o ciclo de vida do aplicativo em todas as fases do planejamento, do desenvolvimento, da entrega e da operação. Cada fase depende das demais e elas não são específicas da função. Em uma verdadeira cultura de DevOps, cada função está envolvida de alguma forma em cada fase.

- **Planejamento:** Na fase de planejamento, as equipes de DevOps idealizam, definem e descrevem os recursos e as funcionalidades dos aplicativos e sistemas que estão construindo. Acompanham o progresso em níveis altos e baixos de granularidade, desde tarefas de produto único até tarefas que abrangem portfólios de vários produtos. Criar listas de pendências, acompanhar bugs, gerenciar o desenvolvimento de software Agile com o Scrum, usar quadros Kanban e visualizar o progresso com painéis são algumas das maneiras pelas quais as equipes de DevOps planejam com agilidade e visibilidade.
- **Desenvolvimento:** A fase de desenvolvimento inclui todos os aspectos da codificação – gravação, teste, revisão e integração do código pelos membros da equipe – bem como a compilação do código em artefatos de compilação, que podem ser implementados em vários ambientes. As equipes de DevOps buscam inovar rapidamente sem sacrificar a qualidade, a estabilidade e a produtividade. Para fazer isso, elas usam ferramentas extremamente produtivas, automatizam etapas elementares e manuais e iteram em pequenos incrementos por um meio de testes automatizados e integração contínua.
- **Entrega:** A entrega é o processo de implantação de aplicativos nos ambientes de produção de maneira consistente e confiável. A fase de entrega também inclui a implantação e a configuração da infraestrutura fundamental totalmente governada que compõe esses ambientes. Na fase de entrega, as equipes definem um processo de gerenciamento de versão com estágios claros de aprovação manual. Elas também definem portões automatizados que movem os aplicativos entre os estágios, até que sejam disponibilizados aos clientes. A automação desses processos os torna escalonáveis, repetíveis e controlados. Dessa forma, as equipes que praticam o DevOps podem frequentemente atuar e entregar com facilidade, confiança e tranquilidade.
- **Operação:** A fase de operação envolve manter, monitorar e solucionar problemas de aplicativos em ambientes de produção. Ao adotar as práticas de DevOps, as equipes trabalham para garantir a confiabilidade do sistema, a alta disponibilidade e o objetivo de tempo de inatividade igual a zero, reforçando a segurança e a governança. As equipes de DevOps buscam identificar os problemas antes que eles afetem a experiência do cliente e mitigar os problemas rapidamente quando ocorrem. Manter esse nível de vigilância requer telemetria avançada, alertas acionáveis e visibilidade total sobre os aplicativos e o sistema subjacente.

## CI CD

É um termo abrangente que cobre várias áreas CI integração continua é a prática de integrar alterações de código em um repositório várias vezes ao dia.

Repositório: Nexus

## SRE

Engenharia de confiabilidade de sites (**SRE**) é uma abordagem da engenharia de software às operações de TI. As equipes de **SRE** usam software como uma ferramenta para gerenciar sistemas, solucionar problemas e automatizar tarefas operacionais.

Faz  a entrega do software

# Ferramentas Essenciais

## **Jenkins**

É ****um servidor de automação de código aberto. Com o Jenkins, as organizações podem acelerar o processo de desenvolvimento de software automatizando-o. 
O Jenkins gerencia e controla os processos de entrega de software em todo o ciclo de vida, incluindo construção, documento, teste, pacote, estágio, implantação, análise de código estático e muito mais.

### **Principais recursos do Jenkins**

1. **Integração Contínua (CI)**: O Jenkins permite que os desenvolvedores integrem suas alterações de código em um repositório compartilhado várias vezes ao dia. Isso ajuda a identificar problemas de integração mais cedo e a garantir que o código esteja sempre atualizado e funcional.
2. **Entrega Contínua (CD)**: Além da integração contínua, o Jenkins facilita a automação da entrega contínua, permitindo que as alterações de código sejam automaticamente testadas e implantadas em ambientes de teste e produção após a aprovação dos testes.
3. **Automatização de Tarefas**: O Jenkins pode automatizar uma variedade de tarefas relacionadas ao desenvolvimento e implantação, como compilação de código, execução de testes automatizados, criação de artefatos, implantação em servidores, entre outros.
4. **Extensibilidade**: O Jenkins possui um ecossistema rico de plugins que podem ser usados para estender suas funcionalidades. Existem milhares de plugins disponíveis para integração com várias ferramentas e tecnologias.
5. **Agendamento**: Os jobs no Jenkins podem ser agendados para serem executados em horários específicos ou acionados por eventos, como commits em um repositório de controle de versão.
6. **Monitoramento e Relatórios**: O Jenkins fornece informações detalhadas sobre o status das compilações, testes e implantações, permitindo que as equipes monitorem e analisem o progresso e a qualidade do projeto.
7. **Integração com Contêineres e Orquestração**: O Jenkins pode ser integrado a ferramentas de contêineres, como Docker, e plataformas de orquestração, como Kubernetes, para automatizar ainda mais o ciclo de vida de aplicativos.

### **Vantagens do Jenkins:**

- **Código Mais Confiável**: A automação proporcionada pelo Jenkins ajuda a reduzir erros humanos, tornando o código mais confiável e estável.
- **Feedback Rápido**: A integração contínua e os testes automatizados permitem que os desenvolvedores recebam feedback rápido sobre suas alterações de código.
- **Entrega Mais Rápida**: A automação da entrega contínua acelera o processo de implantação de software em ambientes de produção.
- **Flexibilidade e Customização**: Os plugins do Jenkins oferecem flexibilidade para personalizar o fluxo de trabalho e integrar diversas ferramentas.

O Jenkins pode ser instalado em uma variedade de sistemas operacionais e ambientes, e sua configuração é realizada por meio de uma interface web amigável. Ele continua sendo uma ferramenta fundamental para equipes DevOps que buscam melhorar a eficiência e a qualidade de seus processos de desenvolvimento e entrega de software.

## SonarQube

SonarQube é uma plataforma de análise estática de código que **fornece uma visão abrangente da qualidade do software**. Ele analisa o código-fonte em busca de problemas, como vulnerabilidades de segurança, bugs, dívida técnica e, é claro, cobertura de teste.

O SonarQube tem o objetivo de **melhorar a qualidade do código de acordo com regras pré-estabelecidas, realizando diversas análises durante o processo de compilação de aplicação**. Principais benefícios: Identificação de problemas: Identifica bugs, vulnerabilidade de segurança e problemas de conformidade no código-fonte.

## Nexus

- Links
    
    https://help.sonatype.com/en/sonatype-nexus-repository.html
    

Nexus **é um gerenciador de repositório**. Ele permite que você faça proxy, colete e gerencie suas dependências. Utilizamos o Nexus para fazer proxy do nuget.org, maven, docker.io ou outros repositórios de contêineres.

![](..\nexus.png)


O Nexus é uma ferramenta confiável para armazemento de artefatos e repositórios. Além de ser Open Source, o Nexus possui uma boa documentação, apresenta um bom nível de segurança e controle de acesso, e armazena os artefatos no sistema de arquivos.

Ver repositório versão Postgree