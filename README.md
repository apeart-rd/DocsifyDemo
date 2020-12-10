The project provides a scaffolded approach to building Single Page Applications with VueJS.

The accompanying CLI tool provides an interactive shell interface to aid in customizing the generated template and expand the project with component modules as needed.

  

Contents
--------

/\*<!\[CDATA\[\*/ div.rbtoc1607632000961 {padding: 0px;} div.rbtoc1607632000961 ul {list-style: square;margin-left: 0px;} div.rbtoc1607632000961 li {margin-left: 0px;padding-left: 0px;} /\*\]\]>\*/

*   [Template Documentation](#RDVue-TemplateDocumentation)
*   [CLI Documentation](#RDVue-CLIDocumentation)

*   [ROADMAP](#RDVue-ROADMAP)
    *   [Version 0.1 (released)](#RDVue-Version0.1(released)) 
    *   [Version 0.2 (development)](#RDVue-Version0.2(development)) 
    *   [Version 0.3 (TBD)](#RDVue-Version0.3(TBD)) 

  

  

[Template Documentation](https://realdecoy.atlassian.net/wiki/spaces/PFDP/pages/708346218/Template+Schema)
----------------------------------------------------------------------------------------------------------

[CLI Documentation](/wiki/pages/createpage.action?spaceKey=PFDP&title=Contents&linkCreation=true&fromPageId=708182305)
----------------------------------------------------------------------------------------------------------------------

  

* * *

ROADMAP
=======

* * *

Version **0.1** (released) 
---------------------------

This version provides a good starter base with clear separation of Components, Views, Store, Theming, Configuration and First-Party Modules. There is some documentation available within each module’s directory and it is intended for most repeatable pieces (e.g. Components) to be copied and renamed. 

**Template Features** 

*   Minimal documentation within project and externally. 
*   Component with basic style guide 
*   View with basic style guide 
*   Store support with module style guide 
*   Custom theming support. Basic Light and Dark theme boilerplate with hooks into the Store to switch themes on the fly. 

*   Service-pattern style guide. 
*   Environment configuration style guide. Dev and Prod supported out of the box and is easily extensible. 

**CLI Features** 

*   None 

* * *

Version **0.2** (development)  
-------------------------------

A modular approach to the template design is adopted and a CLI tool to create customizable project scaffolding. 

**Template Features** 

*   Documentation within project and linked extended external references on Confluence. 
*   Component types separated into individual packages. Resulting template is a composite of packages and mandatory configuration necessary to create a new project scaffold.   Modules: 

*   Component 
*   View 
*   Store 
*   Custom Theming 
*   Configuration (non-optional)   

*   Vuetify theming module. This will be an alternative to the Custom Theming module to use a predefined UI widget framework.   
*   Basic migration support (see cli-tool for more details).   
*   Unit and E2E test support built-in. 

**CLI Features** 

*   NPM deployment for installation 
*   User credential-based login to access RD repos. 
*   Git pull template resources 
*   Interactive shell to allow customizing the modules desired for the new scaffolding. Recommend defaults will be provided. 
*   Basic migration support to upgrade old templates. **This feature will be limited in it’s first iteration and will only support templates version 0.2 and above** **are guaranteed**. 

* * *

Version 0.3 (TBD) 
------------------

Expected: 

*   Greater migration/upgrade support. 

Suggestions: 

*   Internal RD themes