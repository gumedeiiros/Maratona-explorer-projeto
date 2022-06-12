link de bola de cristal

https://gist.githubusercontent.com/maykbrito/0acdf4ce919838ffed50915a31fc5b23/raw/6f4dd01ec3116428ec4c99255944cb9ac7927590/cristal-ball.svg 

# codigo HTML do projeto ( AULA 1 )
<img src="https://gist.githubusercontent.com/maykbrito/0acdf4ce919838ffed50915a31fc5b23/raw/6f4dd01ec3116428ec4c99255944cb9ac7927590/cristal-ball.svg " alt="Imagem de uma bola de cristal">
<h1>Vou revelar seu destino! </h1>
<p>Clique em fazer pergunta para que seu destino seja revelado.</p>
<input type="text" placeholder="Digite sua pergunta"  />
<button>Fazer Pergunta</button>

##Atualização do codigo HTML para entrada do CSS ( AULA 2 )

<body>
  <div id="container">

<img src="https://gist.githubusercontent.com/maykbrito/0acdf4ce919838ffed50915a31fc5b23/raw/6f4dd01ec3116428ec4c99255944cb9ac7927590/cristal-ball.svg " alt="imagem de uma bola de cristal">
  <h1>Vou revelar seu destino</h1>
  <p>Clique em fazer pergunta para que seu destino seja revelado</p>
  <input type="text"       placeholder="Digite sua pergunta">
   <button>Fazer pergunta</button>


 </div> 
</body>

FOI ADD O BODY E O DIV

# Codigo CSS do projeto ( AULA 2 )

body{
 background-color: black;
 color: white;
 text-align: center;
 font-family: sans-serif;

}
#container {
margin-top: 100px;
width: 80%;
max-width: 400px;
margin-right: auto;
margin-left: auto;
/* pode subistituir o marign-left e right pot "margin-inline"*/
/* border: 2px solid red;
siginificado de cada item do border: 2px ( espessura da borda ), solid ( formato da borda ), red ( cor da borda ) */
}

h1{
  margin-top: 40px;
margin-bottom: 10px;
opacity: 0.9;
}
p{
margin-bottom: 40px;
opacity: 0.7;
}
input, button {
  display: block;
width: 100%;

padding: 20px;
font-size: 20px;
border-radius: 4px;
}
input{
margin-bottom: 20px;


#css

 - Apresentação visual para o cliente 

 - Estilo para o HTML
 - cascading style sheets
 - Folha de estilo em cascata (cascata e a ordem que sew coda o css, porém tem a especificidade de cada tag )

- Declaração 
  seletor ( button )
  Propriedade e valor


- Conceitos
  cascata ( id, )
  especificidade( Peso da tag)
  box model ( tudo são caixas, )

## Javascript

- Variaveis
   - let esta chovendo = "true"
   - const meu Nome = "mayk"
   - console.log(meuNome)

- Tipos de dados
  - string
  - " "
  - ' '

- Number
  - 12 - integer ( + -)
  - 3.2 - float (+ - )

- Boolean
  - true ou fslse
  - const maiorDeDezoito = False

- Undefined - indefinido

- Operadores
  - atribuições (ex: =)
  - Atribui valor
  - let n1 = 12 ( let n1 RECEBE 12,)
  - let n2 = 3 (let n2 RECEBE 3)

- Aritimeticos (ex: * / + - )
  - calculos matematicos simples 

- Concatenação de string (+)

- Comparação (ex: > < = )
  - Transforma a expressão em true ou false
  - const maiorQue = 1 > 2 // false
  - const igualA = 1 = 1 // true

- Condicional (if/else)
  - const idade = 17
  const maiorDeDezoito = idade >= 18

  if(maiorDeDezoito) {
    alert ("Pode tirar carteira de motorista")
  } else{
    alert("Não pode tirar")
  }

- Estruturas de dados
  - Array - Vetor - Lista
    _  Array -----     0     1   2    3 
       - const temperaturas = [23.3, 32,2, 1, 5 ]
         console.llog(temperaturas[2])  NUMERO DENTRO DO COLCHETES "2" É A ONDEM DA TEMPERATURA QUE NESSE CASO SERIA 32.2


- Object
  - const pessoa = {
    nome: "mayk", 
    idade: 38,
    filhos: ["K", "E", "J", "L"]
  }
     console.log(pessoa.filhos[3]) NESSE CASO O NUMERO "3" REPRESENTA O FILHO "J". 


- Function
  - Criação 
    Function nomeDaFuncao()  [
      console.log( 'codigo da função)
    ]
  - Execução
     nomeDaFuncao()
     nomeDaFuncao()
     nomeDaFuncao()
NESSA FUNÇÃO SÓ E NECESSARIO ALTERAR NA CRAÇÃO PARA QUE TODA A EXECUÇÃO MUDE INDEPENDENTE DA QUANTIDADE DE EXECUÇÕES.


-Parametros
 Function soma(a, b){
  console.log(a + b)
 }
    soma(34, 45)
    soma(90, 54)


- Retorno
  - Function soma(a, b) {
    return a + b
  }
    const multiplica = soma(2, 2) * 4
      console.log(multiplix)

- Extensoes de linguagem (ex: Math, Date ... )
  - math.randon() gera numero randomico entre 0 e 1
  - math.floor(1.2) Arrendonda para baixo
  - math.ceil(1.2) Arredonda para cima
  -math.PI Numero do PI 3,14...


- Document object model
  - window
  - window.alert("alerta")
  - Document
  - Document.write("texto")
  - Manipular elemwntos
    docume].DocumentElement.style.backgroud = "black"





## Codigo de um projeto paralelo ao do curso maratona rocket seat AULA 1

<img src="https://tribunapr.uol.com.br/wp-content/uploads/sites/81/2021/11/24135331/Boi-Chifre_baixaResolucao.jpg" alt="imagem de um boi"
width="400px">
<h1>Voce é corno?</h1>
<p>Se tem desconfiança digite no campo de pesquisa e clique no "saiba mais"</p>
<input type="text" placeholder="A curiosidade matou o gato" >
<button>Saiba mais</button>


## Codigo CSS do projeto paralelo

body{
background-color:gray;
color: black;
text-align: center;
font-family: sans-serif;
}
#container
{
margin-top: 120px;
width: 75%;
max-width: 350px;
margin-inline: auto;
}
h1{
margin-top: 40px;
margin-bottom: 15px;
opacity: 0.9;
}
p{
margin-top: 25px;
margin-bottom: 15;
opacity: 0.7;
font-size: 25px;
}
input, button {
display: block;
width: 90%;
text-align: center;
margin-inline: auto;
padding: 15px;
font-size: 15px;
border-radius: 3.5px;
}
input{
  margin-bottom: 10px;
  background-color: red;
  color: black;
 font-size: 20px;
}
button{
  background-color: black;
  color: red;
  font-size: 20px;
  transition: filter 0.2s;
}

button:hover{
filter: brightness(1.2);
cursor: pointer;

}
