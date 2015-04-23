# Validate.js
A JQuery library for validating text form inputs.  

- develper defines rules for each input that is then submitted with the form. 
- Validate.js tests each input and stops when a test fails providing the user usful feed back as to why the test fails.
- human readable ids are taken from <label> for feedback 
- Editable functions for PASS and FAIL to tailor to your project.

	<H3>RULES</H3>


<table>
	<thead>
		<tr>
			<th>Options</th>
			<th>pass</th>
			<th>discription</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			
				 <tr><td>required</td><td>	bool		</td><td>check exists	
			</td></tr><tr><td>contains</td><td>	string		</td><td>contains substring at least somewhere in it (regardless of case). 	
			</td></tr><tr><td>endsIn</td><td>	string		</td><td>contains substring at the end (regardless of case). 	
			</td></tr><tr><td>max</td><td>	int				</td><td>make sure string length is more than x	
			</td></tr><tr><td>min</td><td>	int				</td><td>make sure string length is less than x
			</td></tr><tr><td>alpha</td><td>	bool			</td><td>make sure string is just letters 
			</td></tr><tr><td>numeric</td><td>	bool		</td><td>make sure string is just numbers 
			</td></tr><tr><td>numeric_s</td><td>	bool		</td><td>make sure string is just numbers 
			</td></tr><tr><td>max_val</td><td>	int			</td><td>maximum numeric value
			</td></tr><tr><td>min_val</td><td>	int			</td><td>maximum numeric value
			</td></tr><tr><td>alphanumeric_S</td><td>bool	</td><td>make sure string is just letters/numbers & spaces
			</td></tr><tr><td>alphanumeric</td><td>	bool	</td><td>make sure string is just letters/numbers 
			</td></tr><tr><td>letters</td><td>	int			</td><td>makes sure there is x amount of letters
			</td></tr><tr><td>upperletters</td><td>	int		</td><td>makes sure there is x amount of capital letters
			</td></tr><tr><td>lowerletters</td><td>	int		</td><td>makes sure there is x amount of lower case letters
			</td></tr><tr><td>numbers</td><td>	int	     	</td><td>makes sure there is x amount of numbers
			</td></tr><tr><td>nospace</td><td>	bool	 	</td><td>disallows spaces 
			</td></tr><tr><td>email</td><td>	bool	 		</td><td>check if valid email
			</td></tr><tr><td>equalto</td><td>	ID 	 		</td><td>checks to inputs are the same
			</td></tr><tr><td>Notequal</td><td>	ID 	 		</td><td>checks to inputs are Not the same
			</td></tr><tr><td>pair</td><td>	ID				</td><td>requires at least 1 of inputs 
			</td></tr><tr><td>notbefore</td><td> 	ID:date	</td><td>checks date is not before date element		
			</td></tr><tr><td>notafter</td><td>  	ID:date	</td><td>checks date is before date element
			</td></tr><tr><td>regex</td><td>	regex	 		</td><td>takes regex sting and compares		
			</td></tr><tr><td>			</tr>
	</tbody>
</table>





