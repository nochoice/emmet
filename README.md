# Emmet
* please create an class called `Emmet`
* this class
** should have `constructor` with one parameter of type string
** should have one public method called `parse` with one string parameter

## Parse method
Has one string parameter which on the input gets an `emmet string` and it's output should be regular `html`
The input will look like: 
`table>tr>td*2`

and the autput should be:
```
<table>
	<tr>
		<td></td>
		<td></td>
	</tr>
</table>
```
Please use [typescript](https://www.typescriptlang.org/). 
More about [emmet](http://docs.emmet.io/)  you can find here

