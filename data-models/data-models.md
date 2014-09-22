### Avi thinks:

* Seems like we're looking at a relational database. A user will be a simple model, but a user's preferences and identity features will be associated with them via many-to-many relationships. This could be complicated... but it also gets us away from binaries.
* In general - what's our operating assumption about 'attraction'? Is the baseline assumption that everyone's attracted to everyone, and we reduce the pool based on specific exclusions? OR is a new user assumed to be attracted to NO ONE until they provide specific info about what they're looking for. An opt-in to specific pools of potential partners. 

### Lucian answers Avi with an opinion:

* I suggest that gender require that the user check at least one box, and start (in the code) from the assumption that you're attracted to no-one.  It's additive.  However, the rest of the features then remove/filter according to what users check off.  

* To give a concrete example of the above, let's say that I sign up for the site and check off my genders as Woman --> Trans && Genderqueer --> Non-Binary, then I check off my date's genders as Woman --> All && Man --> Not Trans && Intersex.  Now I will only see users whose genders are women OR cis men OR intersex, AND who are attracted to trans women OR non-binary.  Next, in relationship styles, I select poly.  So out of the pool that I got from the gender selector, I now only see users who also checked off poly. What does everybody else think?