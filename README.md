# PeakFlow-TMRE
Poject TMRE - TMS Payload Regular Expression


Using Regular Expressions
This section describes regular expressions that you can use in Sightline and TMS. A regular expression is a text string that describes a search pattern.

In this section
This section contains the following topics:

[Sightline Regular Expressions](https://antiddos.embratel.net.br/arborhelp/content/sp_ug/appendix_regularexpressions/sp_regular_expressions.htm?TocPath=Sightline%2520and%2520TMS%2520User%2520Guide%257CAppendixes%257CUsing%2520Regular%2520Expressions%257C_____1)

[TMS Regular Expressions](https://antiddos.embratel.net.br/arborhelp/content/sp_ug/appendix_regularexpressions/tms_regular_expressions.htm?TocPath=Sightline%2520and%2520TMS%2520User%2520Guide%257CAppendixes%257CUsing%2520Regular%2520Expressions%257C_____2)

[Payload Regular Expressions](https://antiddos.embratel.net.br/arborhelp/content/sp_ug/appendix_regularexpressions/payload_regular_expressions.htm?TocPath=Sightline%2520and%2520TMS%2520User%2520Guide%257CAppendixes%257CUsing%2520Regular%2520Expressions%257C_____3)

[HTTP Header Regular Expressions](https://antiddos.embratel.net.br/arborhelp/content/sp_ug/appendix_regularexpressions/http_header_regular_expressions.htm?TocPath=Sightline%2520and%2520TMS%2520User%2520Guide%257CAppendixes%257CUsing%2520Regular%2520Expressions%257C_____4)

[DNS Regular Expressions](https://antiddos.embratel.net.br/arborhelp/content/sp_ug/appendix_regularexpressions/dns_regular_expressions.htm?TocPath=Sightline%2520and%2520TMS%2520User%2520Guide%257CAppendixes%257CUsing%2520Regular%2520Expressions%257C_____5)

[AS Regular Expressions](https://antiddos.embratel.net.br/arborhelp/content/sp_ug/appendix_regularexpressions/as_regular_expressions.htm?TocPath=Sightline%2520and%2520TMS%2520User%2520Guide%257CAppendixes%257CUsing%2520Regular%2520Expressions%257C_____6)


<h1 style="margin: 10px 10px 0px 0px; text-align: left; font-size: 1.802em; line-height: 1em; font-weight: normal; color: rgb(0, 0, 0); font-family: Arial, &quot;Helvetica Neue&quot;, Helvetica, sans-serif; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: normal; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;"><span class="mc-variable ArborProductVariables.SP_Short variable">Sightline</span><span> </span>Regular Expressions</h1><p style="margin: 0.5em 0px; color: rgb(51, 51, 51); font-family: Arial, &quot;Helvetica Neue&quot;, Helvetica, sans-serif; font-size: 14px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: normal; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;">You can use regular expressions to search text for patterns and certain words or characters.<span> </span><span class="mc-variable ArborProductVariables.SP_Short variable">Sightline</span><span> </span>uses regular expressions to match interfaces and other objects and uses a POSIX regular expression syntax.</p><div class="MCDropDown dropDown MCDropDown_Open" data-mc-state="open" style="color: rgb(51, 51, 51); font-family: Arial, &quot;Helvetica Neue&quot;, Helvetica, sans-serif; font-size: 14px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: normal; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;"><span class="MCDropDownHead dropDownHead" style="display: block; margin-top: 1em; margin-bottom: -0.5em; text-decoration: none;"><a href="javascript:void(0)" class="MCDropDownHotSpot dropDownHotspot MCDropDownHotSpot_ MCHotSpotImage" aria-expanded="true" aria-controls="mc-dropdown-body433950de-6180-4c92-a28a-9619d3d3202c" role="button" style="cursor: pointer; background-repeat: no-repeat; margin-top: 0px; margin-bottom: 0px; margin-left: 0px; font-weight: normal; font-size: 1.27em; line-height: 1.4em; color: rgb(0, 0, 0); text-decoration: none; background-position: left center; background-image: url(&quot;down_arrow.png&quot;); padding-left: 1px; padding-right: 0px;"><img class="MCDropDown_Image_Icon" src="https://antiddos.embratel.net.br/arborhelp/Skins/Default/Stylesheets/Images/transparent.gif" height="13" width="16" alt="Open" data-mc-alt2="Closed" style="border: none;">Syntax examples of regular expressions</a></span><div class="MCDropDownBody dropDownBody" id="mc-dropdown-body433950de-6180-4c92-a28a-9619d3d3202c" style="margin-left: 18px; overflow: hidden; display: block;"><p style="margin: 0.5em 0px;">The following examples explain how you can use regular expressions in<span> </span><span class="mc-variable ArborProductVariables.SP_Short variable">Sightline</span>:</p>
Regular Expression | Description
-- | --
^backbone | Matches an interface name that starts with the word backbone.
^(peer\|transit)-link-[0-9]+ | Matches an interface name that starts with either peer or transit, is followed by -link- and has at least one or more numbers 0-9.
([bB]oston\|[cC]hicago) | Matches either Boston or Chicago, but ignores the case of the first character in the city name.
cust.*boundary | Matches a string that contains the word cust separated by zero or more characters from the word boundary.

</div></div><div class="MCDropDown dropDown MCDropDown_Open" data-mc-state="open" style="color: rgb(51, 51, 51); font-family: Arial, &quot;Helvetica Neue&quot;, Helvetica, sans-serif; font-size: 14px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: normal; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;"><span class="MCDropDownHead dropDownHead" style="display: block; margin-top: 1em; margin-bottom: -0.5em; text-decoration: none;"><a href="javascript:void(0)" class="MCDropDownHotSpot dropDownHotspot MCDropDownHotSpot_ MCHotSpotImage" aria-expanded="true" aria-controls="mc-dropdown-bodye6aa071e-87e6-4d98-b5fd-7093a48b2790" role="button" style="cursor: pointer; background-repeat: no-repeat; margin-top: 0px; margin-bottom: 0px; margin-left: 0px; font-weight: normal; font-size: 1.27em; line-height: 1.4em; color: rgb(0, 0, 0); text-decoration: none; background-position: left center; background-image: url(&quot;down_arrow.png&quot;); padding-left: 1px; padding-right: 0px;"><img class="MCDropDown_Image_Icon" src="https://antiddos.embratel.net.br/arborhelp/Skins/Default/Stylesheets/Images/transparent.gif" height="13" width="16" alt="Open" data-mc-alt2="Closed" style="border: none;">References</a></span><div class="MCDropDownBody dropDownBody" id="mc-dropdown-bodye6aa071e-87e6-4d98-b5fd-7093a48b2790" style="margin-left: 18px; overflow: hidden; display: block;"><p style="margin: 0.5em 0px;">You can access the following resources for more information about regular expressions:</p><ul><li style="margin-top: -0.45em; margin-bottom: 0.2em; margin-left: -1.9em; list-style-type: square;"><p style="margin-top: 0.3em; margin-right: 0px; margin-bottom: inherit; margin-left: 0px;">Wikibooks—Wikibooks provides a detailed description of the Posix Basic Regular Expression language.</p><p style="margin-top: 0.3em; margin-right: 0px; margin-bottom: inherit; margin-left: 0px;"><span class="hypertext" style="text-decoration: underline; color: rgb(5, 99, 193);"><a href="https://en.wikibooks.org/wiki/Regular_Expressions/POSIX_Basic_Regular_Expressions" style="text-decoration: underline; color: rgb(5, 99, 193);">https://en.wikibooks.org/wiki/Regular_Expressions/POSIX_Basic_Regular_Expressions</a></span></p></li><li style="margin-top: 0.25em; margin-bottom: 0.2em; margin-left: -1.9em; list-style-type: square;"><p style="margin-top: 0.3em; margin-right: 0px; margin-bottom: inherit; margin-left: 0px;">Cisco Systems, Inc.—Cisco provides a valuable explanation of regular expressions.</p><p style="margin-top: 0.3em; margin-right: 0px; margin-bottom: inherit; margin-left: 0px;"><span class="hypertext" style="text-decoration: underline; color: rgb(5, 99, 193);"><a href="https://www.cisco.com/c/en/us/td/docs/security/security_management/cs-mars/4-3/user/guide/local_controller/appreexp.html" style="text-decoration: underline; color: rgb(5, 99, 193);">https://www.cisco.com/c/en/us/td/docs/security/security_management/cs-mars/4-3/user/guide/local_controller/appreexp.html</a></span></p></li><li style="margin-top: 0.25em; margin-bottom: 0.2em; margin-left: -1.9em; list-style-type: square;"><p style="margin-top: 0.3em; margin-right: 0px; margin-bottom: inherit; margin-left: 0px;">Wikipedia—This site provides background information about regular expression and syntax examples.</p><p style="margin-top: 0.3em; margin-right: 0px; margin-bottom: inherit; margin-left: 0px;"><span class="hypertext" style="text-decoration: underline; color: rgb(5, 99, 193);"><a href="http://en.wikipedia.org/wiki/Regular_expression" style="text-decoration: underline; color: rgb(5, 99, 193);">http://en.wikipedia.org/wiki/Regular_expression</a></span></p></li></ul></div></div>Sightline Regular Expressions
You can use regular expressions to search text for patterns and certain words or characters. Sightline uses regular expressions to match interfaces and other objects and uses a POSIX regular expression syntax.

Open[Syntax examples of regular expressions](javascript:void(0))
The following examples explain how you can use regular expressions in Sightline:

Examples of regular expression syntax
Regular Expression

Description

^backbone

Matches an interface name that starts with the word backbone.

^(peer|transit)-link-[0-9]+

Matches an interface name that starts with either peer or transit, is followed by -link- and has at least one or more numbers 0-9.

([bB]oston|[cC]hicago)

Matches either Boston or Chicago, but ignores the case of the first character in the city name.

cust.*boundary

Matches a string that contains the word cust separated by zero or more characters from the word boundary.

Open[References](javascript:void(0))
You can access the following resources for more information about regular expressions:

Wikibooks—Wikibooks provides a detailed description of the Posix Basic Regular Expression language.

https://en.wikibooks.org/wiki/Regular_Expressions/POSIX_Basic_Regular_Expressions

Cisco Systems, Inc.—Cisco provides a valuable explanation of regular expressions.

https://www.cisco.com/c/en/us/td/docs/security/security_management/cs-mars/4-3/user/guide/local_controller/appreexp.html

Wikipedia—This site provides background information about regular expression and syntax examples.

http://en.wikipedia.org/wiki/Regular_expression

<h1 style="margin: 10px 10px 0px 0px; text-align: left; font-size: 1.802em; line-height: 1em; font-weight: normal; color: rgb(0, 0, 0); font-family: Arial, &quot;Helvetica Neue&quot;, Helvetica, sans-serif; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: normal; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;">TMS Regular Expressions</h1><p style="margin: 0.5em 0px; color: rgb(51, 51, 51); font-family: Arial, &quot;Helvetica Neue&quot;, Helvetica, sans-serif; font-size: 14px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: normal; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;">You use regular expressions when you configure the following<span> </span><span class="mc-variable ArborProductVariables.TMS_Short variable">TMS</span><span> </span>countermeasures: DNS Scoping, Payload Regular Expression, DNS Regular Expression, HTTP Scoping, and AIF and HTTP/URL Regular Expression.</p><p style="margin: 0.5em 0px; color: rgb(51, 51, 51); font-family: Arial, &quot;Helvetica Neue&quot;, Helvetica, sans-serif; font-size: 14px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: normal; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;"><a class="See_Hdg_context_period MCXref xref xrefSee_Hdg_context_period" href="https://antiddos.embratel.net.br/arborhelp/content/sp_ug/appendix_regularexpressions/payload_regular_expressions.htm" style="color: rgb(5, 99, 193); text-decoration: none;"><span class="mcFormatColor" style="color: rgb(51, 51, 51);">See<span> </span></span><u>Payload Regular Expressions</u><span class="mcFormatColor" style="color: rgb(51, 51, 51);">.</span></a></p><p style="margin: 0.5em 0px; color: rgb(51, 51, 51); font-family: Arial, &quot;Helvetica Neue&quot;, Helvetica, sans-serif; font-size: 14px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: normal; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;"><a class="See_Hdg_context_period MCXref xref xrefSee_Hdg_context_period" href="https://antiddos.embratel.net.br/arborhelp/content/sp_ug/appendix_regularexpressions/http_header_regular_expressions.htm" style="color: rgb(5, 99, 193); text-decoration: none;"><span class="mcFormatColor" style="color: rgb(51, 51, 51);">See<span> </span></span><u>HTTP Header Regular Expressions</u><span class="mcFormatColor" style="color: rgb(51, 51, 51);">.</span></a></p><p style="margin: 0.5em 0px; color: rgb(51, 51, 51); font-family: Arial, &quot;Helvetica Neue&quot;, Helvetica, sans-serif; font-size: 14px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: normal; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;"><a class="See_Hdg_context_period MCXref xref xrefSee_Hdg_context_period" href="https://antiddos.embratel.net.br/arborhelp/content/sp_ug/appendix_regularexpressions/dns_regular_expressions.htm" style="color: rgb(5, 99, 193); text-decoration: none;"><span class="mcFormatColor" style="color: rgb(51, 51, 51);">See<span> </span></span><u>DNS Regular Expressions</u><span class="mcFormatColor" style="color: rgb(51, 51, 51);">.</span></a></p><p style="margin: 0.5em 0px; color: rgb(51, 51, 51); font-family: Arial, &quot;Helvetica Neue&quot;, Helvetica, sans-serif; font-size: 14px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: normal; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;"><span class="mc-variable ArborProductVariables.TMS_Short variable">TMS</span><span> </span>uses a PCRE syntax. This topic describes some of the PCRE syntax.</p><div class="MCDropDown dropDown MCDropDown_Open" data-mc-state="open" style="color: rgb(51, 51, 51); font-family: Arial, &quot;Helvetica Neue&quot;, Helvetica, sans-serif; font-size: 14px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: normal; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;"><span class="MCDropDownHead dropDownHead" style="display: block; margin-top: 1em; margin-bottom: -0.5em; text-decoration: none;"><a href="javascript:void(0)" class="MCDropDownHotSpot dropDownHotspot MCDropDownHotSpot_ MCHotSpotImage" aria-expanded="true" name="kanchor869" aria-controls="mc-dropdown-bodyb77ab29e-74bc-4cd6-abf8-8da0139ecb59" role="button" style="cursor: pointer; background-repeat: no-repeat; margin-top: 0px; margin-bottom: 0px; margin-left: 0px; font-weight: normal; font-size: 1.27em; line-height: 1.4em; color: rgb(0, 0, 0); text-decoration: none; background-position: left center; background-image: url(&quot;down_arrow.png&quot;); padding-left: 1px; padding-right: 0px;"><img class="MCDropDown_Image_Icon" src="https://antiddos.embratel.net.br/arborhelp/Skins/Default/Stylesheets/Images/transparent.gif" height="13" width="16" alt="Open" data-mc-alt2="Closed" style="border: none;">Regular expression anchors</a></span><div class="MCDropDownBody dropDownBody" id="mc-dropdown-bodyb77ab29e-74bc-4cd6-abf8-8da0139ecb59" style="margin-left: 18px; overflow: hidden; display: block;"><p class="stem" style="margin: 0.5em 0px -0.1em;">The following table lists the regular expression anchors:</p>
Characters | Meaning | Example | Effect
-- | -- | -- | --
^ | Start of line | ^arbor | Matches arbor123, but not 123arbor
$ | End of line | arbor$ | Matches 123arbor, but not arbor123
\b | Word boundary | \barbor\b | Matches arbor, but not arbor123
\B | Not word boundary | \barbor\B | Matches arbor123, but not arbor or 123arbor123
\Barbor\B | Matches 123arbor123, but not 123arbor

<p class="note" data-mc-autonum="Note" style="margin: 0.55em 0px 0.8em; position: relative; padding-bottom: 0px; padding-left: 5px; border-left: 3px solid rgb(0, 0, 0);"><span class="autonumber"><span class="note_head" style="display: block; margin-bottom: 0px; font-weight: bold; color: rgb(0, 0, 0);">Note</span></span>Logical AND is not supported.</p></div></div><div class="MCDropDown dropDown MCDropDown_Open" data-mc-state="open" style="color: rgb(51, 51, 51); font-family: Arial, &quot;Helvetica Neue&quot;, Helvetica, sans-serif; font-size: 14px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: normal; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;"><span class="MCDropDownHead dropDownHead" style="display: block; margin-top: 1em; margin-bottom: -0.5em; text-decoration: none;"><a href="javascript:void(0)" class="MCDropDownHotSpot dropDownHotspot MCDropDownHotSpot_ MCHotSpotImage" aria-expanded="true" aria-controls="mc-dropdown-body9a60b3fc-6120-4b57-b22c-5af09d963117" role="button" style="cursor: pointer; background-repeat: no-repeat; margin-top: 0px; margin-bottom: 0px; margin-left: 0px; font-weight: normal; font-size: 1.27em; line-height: 1.4em; color: rgb(0, 0, 0); text-decoration: none; background-position: left center; background-image: url(&quot;down_arrow.png&quot;); padding-left: 1px; padding-right: 0px;"><img class="MCDropDown_Image_Icon" src="https://antiddos.embratel.net.br/arborhelp/Skins/Default/Stylesheets/Images/transparent.gif" height="13" width="16" alt="Open" data-mc-alt2="Closed" style="border: none;">Not supported</a></span><div class="MCDropDownBody dropDownBody" id="mc-dropdown-body9a60b3fc-6120-4b57-b22c-5af09d963117" style="margin-left: 18px; overflow: hidden; display: block;"><p class="stem" style="margin: 0.5em 0px -0.1em;">The following are not supported for<span> </span><span class="mc-variable ArborProductVariables.TMS_Short variable">TMS</span><span> </span>regular expressions:</p><ul><li style="margin-top: -0.6em; margin-bottom: 0.2em; margin-left: -1.9em; list-style-type: square;">Assertions</li><li style="margin-top: 0.25em; margin-bottom: 0.2em; margin-left: -1.9em; list-style-type: square;">Back references</li><li style="margin-top: 0.25em; margin-bottom: 0.2em; margin-left: -1.9em; list-style-type: square;">\p {xx}</li><li style="margin-top: 0.25em; margin-bottom: 0.2em; margin-left: -1.9em; list-style-type: square;">\P {xx}</li><li style="margin-top: 0.25em; margin-bottom: 0.2em; margin-left: -1.9em; list-style-type: square;">\C</li><li style="margin-top: 0.25em; margin-bottom: 0.2em; margin-left: -1.9em; list-style-type: square;">\R</li><li style="margin-top: 0.25em; margin-bottom: 0.2em; margin-left: -1.9em; list-style-type: square;">\K</li></ul></div></div>TMS Regular Expressions
You use regular expressions when you configure the following TMS countermeasures: DNS Scoping, Payload Regular Expression, DNS Regular Expression, HTTP Scoping, and AIF and HTTP/URL Regular Expression.

[See Payload Regular Expressions.](https://antiddos.embratel.net.br/arborhelp/content/sp_ug/appendix_regularexpressions/payload_regular_expressions.htm)

[See HTTP Header Regular Expressions.](https://antiddos.embratel.net.br/arborhelp/content/sp_ug/appendix_regularexpressions/http_header_regular_expressions.htm)

[See DNS Regular Expressions.](https://antiddos.embratel.net.br/arborhelp/content/sp_ug/appendix_regularexpressions/dns_regular_expressions.htm)

TMS uses a PCRE syntax. This topic describes some of the PCRE syntax.

Open[Regular expression anchors](javascript:void(0))
The following table lists the regular expression anchors:

Regular expression anchors
Characters

Meaning

Example

Effect

^

Start of line

^arbor

Matches arbor123, but not 123arbor

$

End of line

arbor$

Matches 123arbor, but not arbor123

\b

Word boundary

\barbor\b

Matches arbor, but not arbor123

\B

Not word boundary

 

\barbor\B

Matches arbor123, but not arbor or 123arbor123

\Barbor\B

Matches 123arbor123, but not 123arbor

Open[Regular expression character classes](javascript:void(0))
The following table lists the regular expression character classes:

Regular expression character classes
Characters

Meaning

Example

Effect

\c

Control character (Ctrl-x)

\cC

Matches Ctrl-C

\s

White space (“ “)

arbor\s123

Matches arbor 123, but not arbor123

\S

Not white space, not (“ “)

arbor\S123

Matches arbors123, but not arbor 123

\d

Digit [0-9]

arbor\d

Matches arbor1 or arbor2, but not 1arbor

\D

Not digit, not [0-9]

\Darbor

Matches aarbor, but not 1arbor

\w

Word [A-Za-z0-9_]

\warbor

Matches 1arbor or aarbor or 12345arbor, but not arbor or @arbor

\W

Not word, not [A-Za-z0-9_]

\Warbor

Matches @arbor, but not 1arbor or aarbor

\xhh

Hexadecimal character hh

\x00\xFF

Matches hex char 00FF

Open[Regular expression quantifiers](javascript:void(0))
The following table lists the regular expression quantifiers:

Regular expression quantifiers
Characters

Meaning

Example

Effect

*

0 or more

arbo*

Matches arb or arbr or arbor or arbooor, but not rbo

+

1 or more

arbo+

Matches arbor or arbooor, but not arbr

?

0 or 1

arbo?

Matches arbor or arbor or arbr, but not rbor or aror

{3}

Exactly 3

a{3}

Matches aaarbor, but not aaaarbor

{3,}

3 or more

a{3,}

Matches aaarbor or aaaaaarbor, but not aarbor

{3,5}

3, 4, or 5

a{3,5}

Matches aaarbor or aaaarbor or aaaaarbor, but not aarbor

Open[Regular expression ranges](javascript:void(0))
The following table lists the regular expression ranges:

Regular expression ranges
Characters

Meaning

Example

Effect

. (period or dot)

Any char except \n (hex \x0a)

a.

Matches arbor or azbor, but not a

(a|b)

a or b

(a|z)

Matches arbor or rboz, but not brbor

(...)

Group of characters

(arb)

Matches arbor or barb, but not aror

[abc]

Range, a or b or c

[abc]

Matches arbor or aabbcc, but not dddd

[^abc]

Range, not a or b or c

[^abc]

Matches dddd or arbor, but not abc

[a-z]

Lowercase letter between a and z

[a-z]

Matches arbor, but not ARBOR

[^a-z]

Not lowercase letter between a and z

[^a-z]

Matches ARBOR or 1234, but not arbor

[A-Z]

Uppercase letter between A and Z

[A-Z]

Matches ARBOR, but not arbor

[^A-Z]

Not uppercase letter between A and Z

[^A-Z]

Matches arbor or 1234, but not ARBOR

[0-9]

Digit between 0 and 9

[0-9]

Matches 1234, but not arbor

[^0-9]

Not digit between 0 and 9

[^0-9]

Matches ARBOR or arbor, but not 1234

Open[Regular expression pattern modifiers](javascript:void(0))
The following table lists the regular expression pattern modifiers:

Regular expression pattern modifiers
Modifier

Description

(?mod)

Turns on modifier for the rest of the expression.

(?-mod)

Turns off modifier for the rest of the expression.

(?mod:<expression>)

Turns on modifier for the expression in <>.

(?-mod:<expression>)

Turns off modifier for the expression in <>.

(?i)

Makes the expression case-insensitive.

Note
HTTP header and payload regular expressions are case‑sensitive by default. To perform case-insensitive matching, preface the expression with “(?i)”.

(?-i)

Makes the expression case-sensitive.

Note
DNS regular expressions are case-insensitive by default. To perform case-sensitive matching, preface the expression with “(?-i)”.

(?#comment)

Adds a comment.

(?m)

Changes the behavior of ^ and $ to match next to newlines within the input string. ^ matches after any newline. $ matches before any newline.

(?s)

Changes the behavior of . (dot) to match all characters, including newlines, within the input string.

Open[Regular expression special characters](javascript:void(0))
The following table lists the regular expression special characters:

Regular expression special characters
Characters

Description

\

Escape character

\a

Alarm BEL char (hex 07)

\e

Escape

\f

Form feed (hex 0C)

\n

New line (hex 0A)

\r

Carriage return (hex 0D)

\t

Tab (hex 09)

[\b]

Backspace

Open[Regular expression metacharacters](javascript:void(0))
The following are metacharacters in regular expressions that must be escaped with “\” or a literal text span:

Regular expression metacharacters
^

$

[

]

?

{

}

(

)

*

\

<

>

+

.

Open[Literal text span](javascript:void(0))
The following table lists the characters used to create a literal text span:

Literal text span characters
Characters

Meaning

Example

\Q

\E

Begin literal string

End literal string

Metacharacters between \Q and \E are escaped

\QGET /cgi/page.cgi?id=1\E

instead of

GET \/cgi\/page\.cgi\?id\=1

Open[Logical OR](javascript:void(0))
The following table contains the logical operator that is used in regular expressions:

Logical operator for regular expressions
Characters

Meaning

Example

Effect

|

Logical OR

(.*\.com|.*\.net)

Matches example.com or example.net

Note
Logical AND is not supported.

Open[Not supported](javascript:void(0))
The following are not supported for TMS regular expressions:

Assertions
Back references
\p {xx}
\P {xx}
\C
\R
\K


<h1 style="margin: 10px 10px 0px 0px; text-align: left; font-size: 1.802em; line-height: 1em; font-weight: normal; color: rgb(0, 0, 0); font-family: Arial, &quot;Helvetica Neue&quot;, Helvetica, sans-serif; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: normal; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;"><span class="SearchHighlight SearchHighlight1" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">Payload</span><span> </span><span class="SearchHighlight SearchHighlight2" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">Regular</span><span> </span><span class="SearchHighlight SearchHighlight3" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">Expression</span>s</h1><p style="margin: 0.5em 0px; color: rgb(51, 51, 51); font-family: Arial, &quot;Helvetica Neue&quot;, Helvetica, sans-serif; font-size: 14px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: normal; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;"><span class="SearchHighlight SearchHighlight1" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">Payload</span><span> </span><span class="SearchHighlight SearchHighlight2" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">regular</span><span> </span><span class="SearchHighlight SearchHighlight3" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">expression</span>s treat the<span> </span><span class="SearchHighlight SearchHighlight1" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">payload</span><span> </span>as a single input string.<span> </span><span class="SearchHighlight SearchHighlight1" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">Payload</span><span> </span><span class="SearchHighlight SearchHighlight2" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">regular</span><span> </span><span class="SearchHighlight SearchHighlight3" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">expression</span>s can match on hex (\x77\x77\x77) characters, ASCII (www) characters, or a combination of both hex and ASCII (\x77w\x77).</p><p style="margin: 0.5em 0px; color: rgb(51, 51, 51); font-family: Arial, &quot;Helvetica Neue&quot;, Helvetica, sans-serif; font-size: 14px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: normal; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;">For information about<span> </span><span class="SearchHighlight SearchHighlight2" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">regular</span><span> </span><span class="SearchHighlight SearchHighlight3" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">expression</span><span> </span>syntax, see<span> </span><a class="Hdg_context MCXref xref xrefHdg_context" href="https://antiddos.embratel.net.br/arborhelp/content/sp_ug/appendix_regularexpressions/tms_regular_expressions.htm" style="color: rgb(5, 99, 193); text-decoration: underline;"><u>TMS<span> </span><span class="SearchHighlight SearchHighlight2" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">Regular</span><span> </span><span class="SearchHighlight SearchHighlight3" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">Expression</span>s</u></a>.</p><div class="MCDropDown dropDown MCDropDown_Open" data-mc-state="open" style="color: rgb(51, 51, 51); font-family: Arial, &quot;Helvetica Neue&quot;, Helvetica, sans-serif; font-size: 14px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: normal; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;"><span class="MCDropDownHead dropDownHead" style="display: block; margin-top: 1em; margin-bottom: -0.5em; text-decoration: none;"><a href="javascript:void(0)" class="MCDropDownHotSpot dropDownHotspot MCDropDownHotSpot_ MCHotSpotImage" aria-expanded="true" aria-controls="mc-dropdown-bodyf36ef423-df1a-4fea-a958-ceb85a8ecb86" role="button" style="cursor: pointer; background-repeat: no-repeat; margin-top: 0px; margin-bottom: 0px; margin-left: 0px; font-weight: normal; font-size: 1.27em; line-height: 1.4em; color: rgb(0, 0, 0); text-decoration: none; background-position: left center; background-image: url(&quot;down_arrow.png&quot;); padding-left: 1px; padding-right: 0px;"><img class="MCDropDown_Image_Icon" src="https://antiddos.embratel.net.br/arborhelp/Skins/Default/Stylesheets/Images/transparent.gif" height="13" width="16" alt="Open" data-mc-alt2="Closed" style="border: none;">Pattern modifiers</a></span><div class="MCDropDownBody dropDownBody" id="mc-dropdown-bodyf36ef423-df1a-4fea-a958-ceb85a8ecb86" style="margin-left: 18px; overflow: hidden; display: block;"><p style="margin: 0.5em 0px;">Multiline and singleline (dotall) pattern modifiers can be used in<span> </span><span class="SearchHighlight SearchHighlight1" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">payload</span><span> </span><span class="SearchHighlight SearchHighlight2" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">regular</span><span> </span><span class="SearchHighlight SearchHighlight3" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">expression</span>s. The multiline modifier (?m) changes the behavior of ^ and $ to match next to newlines within the input string. ^ matches after any newline. $ matches before any newline. The singleline modifier (?s) changes the behavior of . (dot) to match all characters, including newlines, within the input string.</p><p style="margin: 0.5em 0px;"><a class="See_Hdg_context_period MCXref xref xrefSee_Hdg_context_period" href="https://antiddos.embratel.net.br/arborhelp/content/sp_ug/appendix_regularexpressions/tms_regular_expressions.htm#ugappendixd_3042379909_chdiicjh" style="color: rgb(5, 99, 193); text-decoration: none;"><span class="mcFormatColor" style="color: rgb(51, 51, 51);">See<span> </span></span><u><span class="SearchHighlight SearchHighlight2" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">Regular</span><span> </span><span class="SearchHighlight SearchHighlight3" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">expression</span><span> </span>pattern modifiers</u><span class="mcFormatColor" style="color: rgb(51, 51, 51);">.</span></a></p><p style="margin: 0.5em 0px;">The following is an example of a<span> </span><span class="SearchHighlight SearchHighlight1" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">payload</span><span> </span>input string in hex and ASCII format:</p><p class="code" style="margin: 0px 0px 0.5em; font-family: &quot;Courier New&quot;, Courier, &quot;Lucida Sans Typewriter&quot;, &quot;Lucida Typewriter&quot;, monospace; letter-spacing: -0.6px; white-space: pre-wrap;"><span class="code" style="margin-top: 0px; margin-bottom: 0.5em; font-family: &quot;Courier New&quot;, Courier, &quot;Lucida Sans Typewriter&quot;, &quot;Lucida Typewriter&quot;, monospace; letter-spacing: -0.6px; white-space: pre-wrap;">41 63 63 65 70 74 3a 20 2a 2f 2a 0d 0a</span>
                    </p><p class="code" style="margin: 0px 0px 0.5em; font-family: &quot;Courier New&quot;, Courier, &quot;Lucida Sans Typewriter&quot;, &quot;Lucida Typewriter&quot;, monospace; letter-spacing: -0.6px; white-space: pre-wrap;">48 6f 73 74 3a 20 31 2e 31 2e 31 2e 31 0d 0a</p><p class="code" style="margin: 0px 0px 0.5em; font-family: &quot;Courier New&quot;, Courier, &quot;Lucida Sans Typewriter&quot;, &quot;Lucida Typewriter&quot;, monospace; letter-spacing: -0.6px; white-space: pre-wrap;"> </p><p class="code" style="margin: 0px 0px 0.5em; font-family: &quot;Courier New&quot;, Courier, &quot;Lucida Sans Typewriter&quot;, &quot;Lucida Typewriter&quot;, monospace; letter-spacing: -0.6px; white-space: pre-wrap;"><span class="code" style="margin-top: 0px; margin-bottom: 0.5em; font-family: &quot;Courier New&quot;, Courier, &quot;Lucida Sans Typewriter&quot;, &quot;Lucida Typewriter&quot;, monospace; letter-spacing: -0.6px; white-space: pre-wrap;">Accept: */*\r\n</span>
                    </p><p class="code" style="margin: 0px 0px 0.5em; font-family: &quot;Courier New&quot;, Courier, &quot;Lucida Sans Typewriter&quot;, &quot;Lucida Typewriter&quot;, monospace; letter-spacing: -0.6px; white-space: pre-wrap;">Host: 192.168.0.1\r\n</p><p style="margin: 0.5em 0px;">The following table contains<span> </span><span class="SearchHighlight SearchHighlight2" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">regular</span><span> </span><span class="SearchHighlight SearchHighlight3" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">expression</span>s and their results when applied to the preceding<span> </span><span class="SearchHighlight SearchHighlight1" style="color: rgb(255, 255, 255); font-weight: bold; background: -webkit-linear-gradient(top, rgb(89, 128, 0) 0%, rgb(89, 128, 0) 100%);">payload</span><span> </span>string:</p>
Regular Expression | Result
-- | --
^\x41.*\x2f\x2a\x0d$ | Fails because the first line in the payload input string begins with 41 but does not end with 2f 2a 0d.
(?m)^\x41.*\x2f\x2a\x0d$ | Succeeds because the first line in the payload input string begins with 41 and the multiline modifier (?m) causes $ to match 2f 2a 0d before a newline (0a).
\x41\x63.*\x48\x6f | Fails because the first line of the payload input string contains 41 63 but does not contain the string 48 6f.
(?s)\x41\x63.*\x48\x6f | Succeeds because the first line of the payload input string contains 41 63, the second line contains 48 6f, and the singleline modifier (?s) causes (dot) to match all characters between these two strings including the newline (0a).

</div></div>Payload Regular Expressions
Payload regular expressions treat the payload as a single input string. Payload regular expressions can match on hex (\x77\x77\x77) characters, ASCII (www) characters, or a combination of both hex and ASCII (\x77w\x77).

For information about regular expression syntax, see [TMS Regular Expressions](https://antiddos.embratel.net.br/arborhelp/content/sp_ug/appendix_regularexpressions/tms_regular_expressions.htm).

Open[Pattern modifiers](javascript:void(0))
Multiline and singleline (dotall) pattern modifiers can be used in payload regular expressions. The multiline modifier (?m) changes the behavior of ^ and $ to match next to newlines within the input string. ^ matches after any newline. $ matches before any newline. The singleline modifier (?s) changes the behavior of . (dot) to match all characters, including newlines, within the input string.

[See Regular expression pattern modifiers.](https://antiddos.embratel.net.br/arborhelp/content/sp_ug/appendix_regularexpressions/tms_regular_expressions.htm#ugappendixd_3042379909_chdiicjh)

The following is an example of a payload input string in hex and ASCII format:

41 63 63 65 70 74 3a 20 2a 2f 2a 0d 0a
                    

48 6f 73 74 3a 20 31 2e 31 2e 31 2e 31 0d 0a

 

Accept: */*\r\n
                    

Host: 192.168.0.1\r\n

The following table contains regular expressions and their results when applied to the preceding payload string:

Pattern modifier examples
Regular Expression	
Result

^\x41.*\x2f\x2a\x0d$

Fails because the first line in the payload input string begins with 41 but does not end with 2f 2a 0d.

(?m)^\x41.*\x2f\x2a\x0d$

Succeeds because the first line in the payload input string begins with 41 and the multiline modifier (?m) causes $ to match 2f 2a 0d before a newline (0a).

\x41\x63.*\x48\x6f

Fails because the first line of the payload input string contains 41 63 but does not contain the string 48 6f.

(?s)\x41\x63.*\x48\x6f

Succeeds because the first line of the payload input string contains 41 63, the second line contains 48 6f, and the singleline modifier (?s) causes (dot) to match all characters between these two strings including the newline (0a).

Open[About matching DNS queries in payload regular expressions](javascript:void(0))
In DNS queries, the byte right before each label indicates the length of the label. \x03 indicates that the next label is 3 bytes long. A domain query for www.netscout.com would be \x03www\x0dnetscout\x03com. For example, 10 byte labels are preceded by \x0a, and 13 byte labels are preceded by \x0d. However, in plain text, \x0a and \x0d are \n (newline) and \r (carriage return) respectively. Be sure to use the proper hex values for the field length fields or use the (?s) singleline (dotall) pattern modifier to allow “.” to match a newline. Example: (?s)www.netscout.com.

Open[Examples of payload regular expressions](javascript:void(0))
The following table lists different attacks and the regular expression that could be used against them:

Payload regular expression examples
Attack

Regular Expressions

DNS attack to mail.netscout.com

\x04mail\x0dnetscout\x03com

or

(?s)mail.netscout.com

HTTP attack to www.netscout.com

www\x2enetscout\x2ecom

or

\x77\x77\x77\x2enetscout\x2e\x63\x6f\x6d

Open[DNS record types](javascript:void(0))
DNS reflection/amplification attacks often use Type=ANY, where the type field is "00ff" for ANY. To mitigate this type of attack, use the following regular expression: domain\x03com\x00\x00\xff

The following are common DNS record types that would appear in attacks with the HEX value that you would use to match them in the regular expression:

HEX values matches to DNS record types
DNS Record Type

HEX Value

Description

A

\x01

IPv4 address record

AAAA

\x1c

IPv6 address record

MX

\x0f

mail exchange record

NS

\x02

name server record

PTR

\x0c

pointer record

SOA

\x06

start of [a zone of] authority record

TXT

\x10

text record
