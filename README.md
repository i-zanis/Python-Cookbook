# Python-Cookbook

import re
 def titlecase(s):
return re.sub(r"[A-Za-z]+('[A-Za-z]+)?",                  lambda mo: mo.group(0).capitalize(),                  s)

titlecase("they're bill's friends.")
"They're Bill's Friends."
