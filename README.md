# DDD

# O QUE É DDD? 
é uma forma de desenvolver o software com orientação ao domain, modelomos o software com base a orientação ao domain, o ddd é bastante utilizado com microserviços
(ler um pouco sobre domain driver design distilled) 

## COMPLEXIDADE DE SOFTWARES
-O DDD deve ser aplicado a casos de projetos de softwares complexos.
-Bom o ddd é usual quando fazemos softwares que tem as regras de negocios unicas, por exemplo na emserh eu tenho regras de negocios unicas, uma vez que ela utiliza suas proprias regras, diferente de softwares simples, como eu uma padaria, de certa forma uma padaria tem a mesma regra e pode ser habituado facilmente a outras padarias.
-Não tem como utilizar tecnicas avançadas em projetos de alta complexidade. 
-Grande parte da complexidade de software não vem de tecnologias, mas sim de comunicação, separação de contextos entendimentos de negocio, por diversos angulos

## COMO O DDD PODE AJUDAR: 
Ajuda entender com profundidade o dominio e subdomios da aplicação
-ter uma linguagem universal entre todos os envolvidos
-Criar um desing mais estrategico da minha aplicação, percebo que tenho um dominio e subdominios.
-Crias um desing tatico, para conseguirmos maioro agregar as entidades e objetos de valor da aplicação, bem como os eventos do dominio
-assim uma vez que temos isso conseguimos entender a complexidade do negocio e a complexidade tecnica.

## DOMINIO VS SUBDOMINIO:
Bom quando o dominio é muito grande percebemos que podemos dividir eles em subdominios, dentro do meu subdominio temos o core doamain, a onde é o coração da minha regra de negocios, o diferencial competitivo da empresa, o core domain é a parte da aplicação se não existisse não importaria o resto exisitir é como na emserh o core domain são ás regras de como calcular cada evento da folha ou a netflix com os filmes.
dentro do subdominios também existe o Support subdomain apoia o dominio ele faz com que a operação do dominio seja possivel. 
temos também o generic subdomain onde ele apoia tanto o core domain quanto o suport domain, ele é facilmente substituivel, são softwares auxiliares, um exemplo é um sistema onde utilizamos algo para gerar os boletos, facilmente podemos utilizar a api de um banco, porém facilmente também podemos trocar a api desse banco pois queremos gerar o boleto em outro banco, isso é generic subdomain.


