# Inline Java Script Language 

As I have used inline javascript language in HTML file itself so it is an inline JavaScript event.
It tells the browser what code to run when the user clicks a button.

<input type="button" name="C" value="C" onclick="op.value=Math.floor(op.value/10)" />
 It divides the value by 10 and rounds it down.
 
For ex :  If op.value = 123, Math.floor(123 / 10) = 12.

On Click Code :  op.value=''  Clears the input	,
                 op.value=Math.floor(op.value/10)	Deletes last digit,
                 op.value+='%' Adds % sign,
                 op.value+='/' Adds division operator

	
