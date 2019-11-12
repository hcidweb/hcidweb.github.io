## Bibliography Setting Guide

Jekyll scholar plugin enables you to represent as many as information you want related to your publications. Refer to the following section. The template of this information is in **_layout** folder. You modify anytime you want. Soomin Kim's 2019 CHI paper has modified as an example. Please look at her bibtex in the bibtex file.

### List of information fields and Current setting
- Title: A title of your publication
	- format: title={Comparing Data from Chatbot and Web Surveys: Effects of Platform and Conversational Style on Survey Response Quality} 
- author: A list of authors. Separate each name with 'and'. 
	- format: author={Kim, Soomin and Lee, Joonhwan and Gweon, Gahgene} 
- type: A type of your publication. It is defined at first on your bib data. Begin with '@'. Please refer to a bib file for more details.
	- If your publication type is 'article', then the site will look for 'journal' data in the bib file. 
	- If your publication type is 'inproceedings', the site will look for 'booktitle' data in the bib file. 
	- Example. 
		- **@article**{kim2019designing, title={...},...,**journal={International Journal of Human--Computer Interaction}**,...}
		- **@inproceedings**{kim2019comparing, title={...},..., **booktitle={Proceedgins of the 2019 CHI Conference on Human Factors in Computing Systems}**,...}
- year: A year that your paper is published.
- abbr.: (Not necessary) An abbreviation of a journal. Duplicated information.
- abstract: An abstract of your papers. The information is hidden. When you click 'Abs', then the information will be displayed.
- html: A link to a relevant html page such as your webpage or a blog posting.
- url: A link to a website that has your paper. This website should allow audiences to read/download your paper. See this information on google scholar or ACM bibtex.
	- format: url={http://doi.acm.org/10.1145/3290605.3300316} 
- organization: An organization publishing your paper. In current settings, if your organization is ACM, then your URL information will be presented as [ACM]. Otherwise, [URL]
- pdf/supp/slides : Each of them has different purposes, but for now we are using pdf only. Hasn't defined which location we will use for the pdf. 
- code: A link to the Github if you open up your programming code. 

