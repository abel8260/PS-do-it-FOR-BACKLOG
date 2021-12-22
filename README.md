# PS-do-it-FOR-BACKLOG v2-0
Abordando metodologia scrum, esse mini sistema estréia um passo a passo de backlog e user stories para o seu projeto. P.S.: Feito com muito carinho para meus pupilos do github. &lt;3              

## Como usar:

-  O código foi feito em html com um tico de bootstrap. 
-  Para usar basta ir adicionando os cards exemplos como este:
         
  ´´´

        <div class="col" style="border: 2px solid black; margin:5px;">
            <div class="card text-white bg-dark mb-3" style="max-width: 18rem;">
                <div class="card-header"><svg class="bi d-block mx-auto mb-1" width="24" height="24"><use xlink:href="#people-circle"/></svg>
                    <p style="text-align: center;"> Ebol</p>
                </div>
                <div class="card-body">
                    <h5 class="card-title">Titulo</h5>
                    <p class="card-text">Decriçao</p>
                </div>
    
            </div>
        </div>
        
 ´´´
 
- Em Ebol você substitui por seu nome
- Titulo é o titulo do post it
- E descriçao você coloca o que for de comentario ou texto mesmo 

## Como implementar uma nova linha de backlog:

- Você adiciona a seguintes linhas:
- Essa acima do primeiro card:
     
  ´´´

        <div class="row row-cols-4">
        
 ´´´


 
         
- E essa abaixo dos 3 cards:
         
  ´´´

      </div>
        
 ´´´
         

 
 
## Como delimitar as colunas dos cards (ou post-its):

- Coloque o seguinte código acima do primeiro card da coluna:

 ´´´

    <div class="col" style="border: 2px solid black; margin:5px;"> 
        
 ´´´
       
         
- E essa abaixo dos  cards:

         
 ´´´

    </div> 
        
 ´´´         


 ## Titulo do app:
 
 - Em "PS.do-it system" vc coloca o nome do seu projeto ou app.  
 

 ´´´
 
          <a href="/" class="d-flex align-items-center my-2 my-lg-0 me-lg-auto text-black  text-decoration-none">
            <svg class="bi me-2" width="40" height="32" role="img" aria-label="Bootstrap"><use xlink:href="#bootstrap"/></svg> PS.do-it system
          </a>


 ´´´

## v2-0 Feature


- Nessa feature temos a questao das seções dentro d e 1 backlog q  ue voce pode conseguir adicionando essalina de codigo ao arquivo html.


 ´´´
 
         <div class="container">
         <br/>
         <hr/>
         <br/>
         </div>    

 ´´´

- Essalinha de codigo  adicionara  um hr . (linha) ao seu front end(visual)  do seu backlog.  Mais informações em breve.  Tchauzinho pimpoooolhos do bel.          
