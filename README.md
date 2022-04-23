<h1>Tratando exceções com JAVA </h1>
<h2>Projeto desenvolvido durante o progresso do Curso Java POO ministrado pelo Dr. Nelio Alves</h2>

<h3>O projeto fora desenvolvido, seguindo:</h3>


<h3> • Solução 1 (muito ruim):</h3>
-> lógica de validação no programa principal<br>
-> Lógica de validação não delegada à reserva

<h3> • Solução 2 (ruim):</h3>
-> método retornando string <br>
-> A semântica da operação é prejudicada<br> 
      --> Retornar string não tem nada a ver com atualização de reserva;<br>	 
      --> E se a operação tivesse que retornar um string?. <br>
 -> Ainda não é possível tratar exceções em construtores<br>
 -> Ainda não há auxílio do compilador: o programador deve "lembrar" de verificar se houve erro<br>
 -> A lógica fica estruturada em condicionais aninhadas<br>

<h3> • Solução 3 (boa):</h3> 
-> tratamento de exceções de forma adequada e de responsabilidade da entidade

---------------------------------

"Desafie seus limites!"
🚀🚀🚀
