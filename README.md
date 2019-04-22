# OCAC_Online_Library

<br/><br/>
A Library Management System for OCAC Librarians and Members
<br/><br/>
#content Structure
<br/>
Pages:
<br/>
-Sign Up Page for Members
<br/>
-Login Page for Members
<br/>
-Update Profiles for Members
<br/>
-Login Page for Libriains
<br/><br/>
Page HTML Layout
<br/>
Login Page:
<br/>
-.contain(#1) // Control the whole login page layout
<br/>
--.info(#2) // display info on desktop view (display none on mobile view)
<br/>
--.login(#2)
---.logo(#3)
---.form(#3)
----.inputControl(#4) // control the layout of username, password and submit btn
---.reset(#3)
<br/><br/>
Sign Up Page:
<br/>
-.contain(#1) // Control the whole Sign Up page layout
<br/>
--.info(#2) // display info on desktop view (display none on mobile view)
<br/>
--.Sign Up(#2)
---.logo(#3)
---.form(#3)
----.row(#4)
-----.inputControl(#5) // control the layout of username, password,email, phone, checkbox and submit btn
------.checkControl(#6) //control checkbox option layout
<br/><br/>
