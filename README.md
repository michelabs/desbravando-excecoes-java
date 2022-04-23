<h1>Tratando exceções com JAVA </h1>
<h2>Projeto desenvolvido durante o progresso do Curso Java POO ministrado pelo Dr. Nelio Alves</h2>

<h3>O projeto fora desenvolvido, seguindo:</h3>


• Solução 1 (muito ruim): lógica de validação no programa principal
 	- Lógica de validação não delegada à reserva

• Solução 2 (ruim): método retornando string
- A semântica da operação é prejudicada<br> 
		-> Retornar string não tem nada a ver com atualização de reserva<br>	 
	 	-> E se a operação tivesse que retornar um string?
	 
 - Ainda não é possível tratar exceções em construtores
 
 - Ainda não há auxílio do compilador: o programador deve "lembrar" de verificar se houve erro
 
 - A lógica fica estruturada em condicionais aninhadas

 - Solução 3 (boa): tratamento de exceções de forma adequada e de responsabilidade da entidade

---------------------------------

"Desafie seus limites!"
🚀🚀🚀