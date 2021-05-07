# Heading1

## Heading2

### Heading3

Paragraph__

* text__
	* text__
* text__

text__
1. text__  
	2. text__	        //github (doesn't process -- without empty newline)
5. text__

	2. text__		//github (language)

		3. text__		//github
		3. text__		//github

			4. text__		//github
6. text__

newLines__
<br />
<br />

\<\> \_text\_

**text__**  
<u>text__</u>		// #underline . githubWiki supports, github_repository_code not  
~~text__~~  
*text__*  
text__ <sup>"superscript"\_\_</sup> <sub>"subscript"\_\_</sub>  

text__ <i><sup><span
         title="text__" style="color:dodgerBlue;">[name__]</span></sup></i>                //github doesn't allow colors

text__ <sup
	 title="text__"><b>[i]</b></sup>

<!--_textOfTheComment__>>-->
[comment]: wordOfTheComment__

|tableHeader__      |tableHeader__      |
|---                |---                |
|text__             |text__             |

<details><summary>shortenedText__
</summary>

text__

</details>

### Linking files, paths

URL Escaping
```
Space 	%20
<	%3C
>	%3E
#	%23
%	%25
{	%7B
}	%7D
|	%7C
\	%5C
^	%5E
~	%7E
[	%5B
]	%5D
`	%60
;	%3B
/	%2F
?	%3F
:	%3A
@	%40
=	%3D
&	%26
$	%24
```

The filename is supported by: Windows, [d Linux] .

1aA\`~!@#$%^&()-\_=+{},. .md

[.md](..//..//assets//github_b//1aA`~!@%23$%25%5E&()-_=+{},.%20.md) -- [Percent-encoding](https://en.wikipedia.org/wiki/Percent-encoding)/URI/URL .

[Folder](..//..//assets//github_b//1aA`~!@%23$%25%5E&()-_=+{},%20.)

[.md](..//..//assets//github_b//1aA`~!@%23$%25%5E&()-_=+{},.&#x20;.md) -- [Space], can be `&#32;`, is from [Numeric character reference](https://en.wikipedia.org/wiki/Numeric_character_reference)/HTML/XML .

[.md](../../assets/github_b/1aA`~!@%23$%25%5E&()-_=+{},.&#32;.md)

![pi](..//..//assets//github_b//co_dw_256x256.png)
