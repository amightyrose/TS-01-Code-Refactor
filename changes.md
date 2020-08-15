# changes.md

This file lists the changes that were made to the index.html and style.css documents


## index.html

* Added a more descriptive title to the `title` tag

* Replaced div elements with the following semantic html elements:
  * `header` and `footer`
  * `nav` for top navigation bar
  * `main` element for central content
  * `aside` element for sections on the right hand side
  * `section` elements inside the `main` and `aside` elements



## style.css

* moved font color into the `body` selector because most of the text on the page is white, removed other references except from the `a` rule*set
* added `font*family` declaration into the `body` rule*set and removed other references, covers most of the text
* changed the `.header h1` rule*set to `h1`
* changed `.header h1 .seo` to `span`
* changed `.header div` to `nav`
* changed `.header div ul` to `ul`
* changed `.header div ul li` to `li`
* changed `.content` to `main`
* combined `.search*engine*optimization/.online*reputation*management/.social*media*marketing` into one `main section` rule*set
* combined `.search*engine*optimization img/.online*reputation*management img/.social*media*marketing img` into one `main img` rule*set
* combined `.search*engine*optimization h2/.online*reputation*management h2/.social*media*marketing h2` into one `main h2` rule*set
* changed  `.benefits` to `aside`
* combined `.benefit*lead/.benefit*brand/.benefit*cost` into one `aside section` rule*set
* combined `.benefit*lead h3/.benefit*brand h3/.benefit*cost h3` into one `aside h3` rule*set
* combined `.benefit*lead img/.benefit*brand img/.benefit*cost img` into one `aside img` rule*set
* changed `.footer` and `.footer h2` to `footer` and `footer h2`
* re-ordered the rule-sets so they are a bit more logical and easy to follow
