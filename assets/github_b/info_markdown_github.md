---
variableName__: line__
variableName_1__: line__
---
// Github . VScode doesn't show . Both require directly at start of file .

<div align=center><h3><b>
Github Markdown Description
</b></h3><b>
[info_markdown] [ver_dev] by Xrud

[English]
</b></div>

This page is dev, but we think its simple enough .

<div style="text-align: center;">HTML Section/Container content</div>

<div align=center>HTML Section/Container content</div>

<p style="text-align: center;">paragraph HTML mark (usually for auto-surrond with vertical indent) content</p>

<p align=center>paragraph HTML mark (usually for auto-surrond with vertical indent) content</p>

# Heading1

## Heading2

### Heading3

Paragraph__

* text__
	* text__
* text__

text__
1. text__  
	2. text__ -- github (doesn't process -- without empty newline)
5. text__

	2. text__ -- github (number's language)

		3. text__ -- github
		3. text__ -- github

			4. text__ -- github
6. text__

newLines__
<br />
<br />

**text__**  
<u>text__</u> : #underline . githubWiki supports, github_repository_code not ;  
~~text__~~  
*text__*  
text__ <sup>"superscript"\_\_</sup> <sub>"subscript"\_\_</sub>  

text__ <i><sup><span
         title="text__" style="color:dodgerBlue;">[name__]</span></sup></i> : github doesn't allow colors . Span -- in-line HTML Section/Container ;

text__ <sup
	 title="text__"><b>[i]</b></sup>

<!--_textOfTheComment__>>-->
[comment]: wordOfTheComment__

|tableHeader__      |tableHeader__      |
|---                |---                |
|text__             |text__             |

<details><summary> shortenedText__
	
</summary>

text__

</details>

## Escaping

### Short

`` \<\> whitespace__\_notWhitespace__ []\() []\[] []\: \` \~~ \|| \--- \* 1\. \$ ``

### Description

`` whitespace__\_notWhitespace__ `` -- to fix/escape [ [whitespace]`_`[notWhitespace] [anything] [notWhitespace]`_` ] .

`` []\[] `` -- highly suggessted to escape, even though its usually not converted without relevant `` [line_notOnlyWhitespace__]: line_notOnlyWhitespace__ `` .

`` \$ `` -- some processors use it as a Math text definition brackets .

`` \~~ \|| `` -- Discord Markdown 101 (each such sequense, even if it continues the previous . escaping each/{by 1} is exessive, as these characters have meanings) .

`` \<> `` -- otherwise its easier to remember, but technicaly second `\` is not needed .

`` \`\` `` -- fist `\` is an escape, and second is to prevent breaking of ` `` ` .

`` \` []\() `` -- other ones which escape too is required even in-line .

`` \--- `` -- global escaping includes tables .

`` \* ``

`` 1\. ``

`` [line_notOnlyWhitespace__]\: line_notOnlyWhitespace__ ``

`` \`\`\` `` -- first `\` is an escape, and the other is to allow `` ` `` and ` `` ` next to it (without separating characters) .

## Linking files, paths

See [linking](assets//linking.md) .
