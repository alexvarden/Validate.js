# Validate.js
A JQuery library for validating text form inputs.  

- develper defines rules for each input that is then submitted with the form. 
- Validate.js tests each input and stops when a test fails providing the user usful feed back as to why the test fails.
- human readable ids are taken from <label> for feedback 
- Editable functions for PASS and FAIL to tailor to your project.


<table> 
 <tr>
	<caption>RULES</caption>
	<thead>
		<tr>
			<th>Options</th>
			<th>pass</th>
			<th>discription</th>
		</tr>
	</thead>
	<tbody>
	
 			<tr>
			required</td><td>bool	check exists	 
			</tr>
			<tr>
			contains</td><td>string  contains substring at least somewhere in it (regardless of case). 	 
			</tr>
			<tr>
			endsIn</td><td>string  contains substring at the end (regardless of case). 	 
			</tr>
			<tr>
			max</td><td>int		make sure string length is more than x	 
			</tr>
			<tr>
			min</td><td>int		make sure string length is less than x 
			</tr>
			<tr>
			alpha</td><td>bool	make sure string is just letters  
			</tr>
			<tr>
			numeric</td><td>bool	make sure string is just numbers  
			</tr>
			<tr>
			numeric_s</td><td>bool	make sure string is just numbers  
			</tr>
			<tr>
			max_val</td><td>int 	maximum numeric value 
			</tr>
			<tr>
			min_val</td><td>int 	maximum numeric value 
			</tr>
			<tr>
			alphanumeric_S</td><td>bool	make sure string is just letters/numbers & spaces 
			</tr>
			<tr>
			alphanumeric</td><td>bool	make sure string is just letters/numbers  
			</tr>
			<tr>
			letters</td><td>int		makes sure there is x amount of letters 
			</tr>
			<tr>
			upperletters</td><td>int		makes sure there is x amount of capital letters 
			</tr>
			<tr>
			lowerletters	int		makes sure there is x amount of lower case letters 
			</tr>
			<tr>
			numbers			int	    makes sure there is x amount of numbers 
			</tr>
			<tr>
			nospace			bool	disallows spaces  
			</tr>
			<tr>
			email			bool	check if valid email 
			</tr>
			<tr>
			equalto			ID 		checks to inputs are the same 
			</tr>
			<tr>
			Notequal		ID 		checks to inputs are Not the same 
			</tr>
			<tr>
			pair			ID		requires at least 1 of inputs  
			</tr>
			<tr>
			notbefore	  ID:date	checks date is not before date element		 
			</tr>
			<tr>
			notafter	  ID:date	checks date is before date element 
			</tr>
			<tr>
			regex 		   regex	takes regex sting and compares
	</tbody>
</table>



 
