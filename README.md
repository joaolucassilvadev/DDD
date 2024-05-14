# DDD

# O QUE É DDD? 

é uma forma de desenvolver o software com orientação ao domain, modelomos o software com base a orientação ao domain, o ddd é bastante utilizado com microserviços
(ler um pouco sobre domain driver design distilled) 

## COMPLEXIDADE DE SOFTWARES

- O DDD deve ser aplicado a casos de projetos de softwares complexos.
- Bom o ddd é usual quando fazemos softwares que tem as regras de negocios unicas, por exemplo na emserh eu tenho regras de negocios unicas, uma vez que ela utiliza suas proprias regras, diferente de softwares simples, como eu uma padaria, de certa forma uma padaria tem a mesma regra e pode ser habituado facilmente a outras padarias.
- Não tem como utilizar tecnicas avançadas em projetos de alta complexidade. 
- Grande parte da complexidade de software não vem de tecnologias, mas sim de comunicação, separação de contextos entendimentos de negocio, por diversos angulos

## COMO O DDD PODE AJUDAR: 

Ajuda entender com profundidade o dominio e subdomios da aplicação
- ter uma linguagem universal entre todos os envolvidos
- Criar um desing mais estrategico da minha aplicação, percebo que tenho um dominio e subdominios.
- Crias um desing tatico, para conseguirmos maioro agregar as entidades e objetos de valor da aplicação, bem como os eventos do dominio
-assim uma vez que temos isso conseguimos entender a complexidade do negocio e a complexidade tecnica.

## DOMINIO VS SUBDOMINIO:

Bom quando o dominio é muito grande percebemos que podemos dividir eles em subdominios, dentro do meu subdominio temos o core doamain, a onde é o coração da minha regra de negocios, o diferencial competitivo da empresa, o core domain é a parte da aplicação se não existisse não importaria o resto exisitir é como na emserh o core domain são ás regras de como calcular cada evento da folha ou a netflix com os filmes.

- dentro do subdominios também existe o Support subdomain apoia o dominio ele faz com que a operação do dominio seja possivel. 

- temos também o generic subdomain onde ele apoia tanto o core domain quanto o suport domain, ele é facilmente substituivel, são softwares auxiliares, um exemplo é um sistema onde utilizamos algo para gerar os boletos, facilmente podemos utilizar a api de um banco, porém facilmente também podemos trocar a api desse banco pois queremos gerar o boleto em outro banco, isso é generic subdomain.
## ESPAÇO DE PROBLEMA VS ESPAÇO DE SOLUÇÃO:

- espaço de problema: é uma visão geral do dominio e suas complexidades, quando eu recebo um problema, primeiro eu devo entender o problema no geral entendendo qual é meu dominio no teotal e depois ir dividindo em subdominios

- espaço de solução: A ideia do espaço de solução é pegar o dominio e fazer a modelagem desse dominio, depois ir dividindo em subdominios, após isso eu delimito para meus subdominios contextos, onde cada subdominio se tem os seus contextos. 
- Resumo: o que entendenmos por espaço de problema e de solução é que ver o problema que temos, começamos a modelar esse problema, separamos esses problema em problemas menores ai demilitamos esses problemas menores em pontos onde vamos começar a desenvolver. Assim temos o dominio modelado, dividido em subdominios e após isso a contextualização desses subdominios, delimitanto esses problemas em subdomnios onde vamos trabalhar com cada questão desse probelma maior.

## O QUE SÃO CONTEXTOS DELIMITADOS: 

-Bounded contexts (contexto delimitados): Bom os bounded context são limites ou fronteiras que temos entre nossos subdominios, tudo que é especifico de um negocio é delimitado por um bounded contexts.

## CONTEXTO É REI: 

- Um contexto sempre vai determinar em qual area da empresa estamos trabalhando e suas regras de negocios.
  
- Vamos supor que temos dois ticket um é de vendas de ingressos e outro de suporte de clientes, logo observamos que temos duas palavras iguais porém com contextos totalmente diferentes, logo observamos que os contextos estão delimitados.vamos supor que criamos uma entidade ticket, como vamos utilizar para os dois contextos?, não utilizamos criamos duas entidades ticket com contextos diferentes e modelagens diferentes.

## ELEMENTOS TRANSVERSAIS: 
parei na aula 423


