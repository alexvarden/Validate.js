# Validate.js
A JQuery library for validating text form inputs.  

- develper defines rules for each input that is then submitted with the form. 
- Validate.js tests each input and stops when a test fails providing the user usful feed back as to why the test fails.
- human readable ids are taken from <label> for feedback 
- Editable functions for PASS and FAIL to tailor to your project.


                              RULES
      ------------------------------------------------------
      Options			    pass 	  discription
			------------------------------------------------------
			required	  	  bool	  check exists	
			contains  		  string  contains substring at least somewhere in it (regardless of case). 	
			endsIn			    string  contains substring at the end (regardless of case). 	
			max				      int		  make sure string length is more than x	
			min 			      int		  make sure string length is less than x
			alpha			      bool  	make sure string is just letters 
			numeric			    bool	  make sure string is just numbers 
			numeric_s	  	  bool	  make sure string is just numbers 
			max_val			    int 	  maximum numeric value
			min_val			    int 	  maximum numeric value
			alphanumeric_S  bool	  make sure string is just letters/numbers & spaces
			alphanumeric	  bool	  make sure string is just letters/numbers 
			letters			    int		  makes sure there is x amount of letters
			upperletters	  int		  makes sure there is x amount of capital letters
			lowerletters	  int		  makes sure there is x amount of lower case letters
			numbers			    int	    makes sure there is x amount of numbers
			nospace			    bool	  disallows spaces 
			email			      bool	  check if valid email
			equalto			    ID 		  checks to inputs are the same
			Notequal		    ID 		  checks to inputs are Not the same
			pair			      ID		  requires at least 1 of inputs 
			notbefore	      ID:date	checks date is not before date element		
			notafter	      ID:date	checks date is before date element
			regex 		      regex	  takes regex sting and compares


