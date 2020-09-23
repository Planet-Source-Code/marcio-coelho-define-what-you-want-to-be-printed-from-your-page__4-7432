<div align="center">

## Define what you want to be printed from your page


</div>

### Description

Using CSS you will be able to say what you want to be printed. Let's say: "What you print is only what you want to be printed"
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Marcio Coelho](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/marcio-coelho.md)
**Level**          |Intermediate
**User Rating**    |4.9 (54 globes from 11 users)
**Compatibility**  |HTML
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__4-1.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/marcio-coelho-define-what-you-want-to-be-printed-from-your-page__4-7432/archive/master.zip)





### Source Code

<HTML>
<HEAD>
<META NAME="GENERATOR" Content="Microsoft Visual Studio 6.0">
<style type="text/css">
<!-- Hide from legacy browsers
.print {
 display: none;
}
/* Specifies how tags with these classes are printed */
@media print {
	/* All the form elements under the class bellow will not be printed */
	.noprint {
	 display: none;
	}
}
/*-->
</style>
</HEAD>
<BODY>
<TABLE>
<TR>
	<TD>This text is to be printed </TD>
	<TD><INPUT id=text1 name=text1 value="show me on paper"></TD>
</TR>
<TR class="noprint">
	<TD> This will not print </TD>
	<TD><INPUT id=text2 name=text2 value="please do not print me"></TD>
</TR>
<TR></TR>
</TABLE>
<INPUT type="button" value="do not print me" id=button1 name=button1 class="noprint" style="WIDTH: 224px; HEIGHT: 24px" size=37><BR>
<INPUT type="button" value="Hei! do not print me either" id=button2 name=button2 class="noprint"><BR>
<P>&nbsp;</P>
</BODY>
</HTML>

