# Documento de Visão  
  
## 1. Objetivo  
O propósito deste software é facilitar o acesso ao condominio pelos moradores e visitantes, abrangendo também as questões de segurança de todos. Será possível cadastrar no software as placas dos veículos autorizados a entrar no condominio e também a digital dos moradores, o que acarretará em menor tempo gasto na parte de fora da portaria aguardando validação e verificação de identidade dos condominos, familiares e amigos.

## 2. Descrição do Problema  
Atualmente os condominos, amigos e familiares precisam apresentar documento de identificação na portaria e aguardar do lado externo do condominio até que a validação de sua permissão de acesso seja verificada, gastando tempo desnecessário, provocando, algumas vezes, filas para entrada e gerando insegurança aos moradores por estarem parados na parte de fora do condominio. 
A solução que o software apresenta irá tornar o acesso ao condominio mais rápido e seguro, através de um cadastro informatizado de veículos e moradores que seram validados por placa e digital respectivamente.

## 3. Definição das Partes Interessadas  

### Cliente  

 1. **Nome**: Anderson
   - **Descrição**: Sindico responsável pelo condominio.
   - **Responsabilidades**: Zelar por toda a área comum do condominio, bem como segurança e portaria, oferecendo segurança e confiabilidade aos moradores.  

 2. **Nome**: Carlos 
   - **Descrição**: Um dos responsáveis pela portaria do condominio 
   - **Responsabilidades**: Monitorar a entrada e saída de pessoas e veículos do condominio, zelando pela segurança do mesmo.

### Time de Desenvolvimento

 1. **Nome**: Carina Emerim Leal 
   - **Descrição**: Análise e desenvolvimento do projeto
   - **Responsabilidades**: Apresenta a ideia para resolver o problema do condominio, desenvolve o mapa de empatia de uma das personas e fabrica o documento de visão referente ao projeto.


## 4. Descrição do Produto  
Para Sindicos e Portaria que necessitam de uma solução eficaz no monitoramento das pessoas e veículos que entram e saem do condominio, o Software Security Control Neo é um sistema de monitoramento informatizado que realiza todo o controle através das placas dos carros que devem ser previamente cadastradas pelos moradores, bem como cadastramento das digitais de moradores, familiares e amigos. Ao contrário dos demais existentes no mercado, o Security Control Neo permite que a validação de identidade seja realizada de maneira extremamente segura e ágil.

## 5. Necessidades e Funcionalidades do Produto  

### 1. Cadastro de Moradores e Funcionários 1  
 - **Benefício**: Critico
 - **Funcionalidades**:  
    1. Cadastramento biométrico 1.1  
       - Atores Envolvidos: Moradores, amigos, familiares e demais pessoas cuja entrada deve ser permitida. 
    2. Exclusão de Cadastro Biométrico 1.2  
       - Atores Envolvidos: Moradores, amigos, familiares e demais pessoas cuja entrada nao deve mais ser permitida.  

### 2. Cadastro de Veículos 2   
 - **Benefício**: Critico 
 - **Funcionalidades**:  
    1. Cadastramento de placa de veículo 2.1  
       - Atores Envolvidos: Moradores, amigos, familiares e demais pessoas cuja entrada deve ser permitida.
    2. Exclusão de Cadastro de placa de veículo 2.2  
       - Atores Envolvidos: Moradores, amigos, familiares e demais pessoas cuja entrada deve ser permitida.  
       
 ### 3. Cadastro de veículo Suspeito 3   
 - **Benefício**: Importante
 - **Funcionalidades**:  
    1. Cadastro de veículo suspeito 3.1  
       - Atores Envolvidos: Moradores e portaria.  
    2. Exclusão de veículo suspeito 3.2  
       - Atores Envolvidos: Moradores e portaria.          

## 6. Proposta de Solução Tecnológica Escolhida  
O projeto envolve um software que rode online e que permita atualizações por parte do síndico. Deverá ser funcional em dispositivos mobiles e navegadores, porém em casos de falta de internet permite o acesso ao banco de dados que já constava atualizado anteriormente para que não se comprometa a utilização.
Também será necessário um leitor biométrico para que seja possível capturar as digitais dos usuários.

## 7. Restrições    
**Funcionais/Negócio** - Deverá haver uma mudança de comportamento das pessoas que irão acessar o condomínio afim de se adaptarem a utilização do leitor biométrico. 
**Tecnológicas** - O aplicativo necessita do leitor biométrico para funcionar adequadamente.  
**Operacionais** - É necessária a correta utilização por parte dos usuários do sistema e pessoas envolvidas, inserir dados confiáveis.
 



