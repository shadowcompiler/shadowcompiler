###
```python
from rest_framework.views import APIView
from rest_framework.response import Response
from rest_framework import status

class AboutMe(APIView):

    def get(self, request):

        shadowcompiler= {
        "fullName": "Salaou-Deen Henri-JoÃ«l Abiodoun PARAISO",
        "stack": { "languages": ['Python', 'Php', 'JS', 'Kotlin'],
                   "tools": ['Django', 'DRF', 'VueJS', 'NuxtJS', 'Bulma', 'Beufy'],
                   "databases": ['Mysql', 'Postgresql', 'Sqlite'],
                   "architectures": ["MVC", "MVT", "REST", "PWA", "SPA"]},        
        "roles": ["Web & Mobile dev as freelance", "Blogger", "Founder at @henrid3v", "Mentor"],
        "askMe": ['Food', 'Manga', 'Science', 'Comics', 'NaturalHair', 'Photography', 'Tech', 'Programming'],
        "contacts": { 'Telegram': 'imsadi',
                       'Linkedin': 'henri-dev',
                       'Discord': 'ShadowCompiler#2596',
                       'Mail':'pariso03henri@gmail.com',}}
        return Response(shadowcompiler, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-0%20secs-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-55%20Thousand%20lines%20of%20code-blue)

**ð± My GitHub Data** 

> ð 317 Contributions in the Year 2022
 > 
> ð¦ 36.0 kB Used in GitHub's Storage 
 > 
> ð¼ Opted to Hire
 > 
> ð 21 Public Repositories 
 > 
> ð 13 Private Repositories  
 > 
**I'm an Early ð¤** 

```text
ð Morning    228 commits    âââââââââââââââââââââââââ   36.42% 
ð Daytime    176 commits    âââââââââââââââââââââââââ   28.12% 
ð Evening    160 commits    âââââââââââââââââââââââââ   25.56% 
ð Night      62 commits     âââââââââââââââââââââââââ   9.9%

```
ð **I'm Most Productive on Friday** 

```text
Monday       98 commits     âââââââââââââââââââââââââ   15.65% 
Tuesday      66 commits     âââââââââââââââââââââââââ   10.54% 
Wednesday    86 commits     âââââââââââââââââââââââââ   13.74% 
Thursday     101 commits    âââââââââââââââââââââââââ   16.13% 
Friday       115 commits    âââââââââââââââââââââââââ   18.37% 
Saturday     99 commits     âââââââââââââââââââââââââ   15.81% 
Sunday       61 commits     âââââââââââââââââââââââââ   9.74%

```


ð **This Week I Spent My Time On** 

```text
âï¸ Time Zone: UTC

ð¬ Programming Languages: 
Vue.js                   4 hrs 5 mins        âââââââââââââââââââââââââ   90.95% 
Markdown                 13 mins             âââââââââââââââââââââââââ   5.08% 
JavaScript               10 mins             âââââââââââââââââââââââââ   3.97%

ð¥ Editors: 
VS Code                  4 hrs 30 mins       âââââââââââââââââââââââââ   100.0%

ð±âð» Projects: 
lemocontrol              4 hrs 30 mins       âââââââââââââââââââââââââ   100.0%

ð» Operating System: 
Linux                    4 hrs 30 mins       âââââââââââââââââââââââââ   100.0%

```

**I Mostly Code in Python** 

```text
Python                   14 repos            âââââââââââââââââââââââââ   40.0% 
CSS                      7 repos             âââââââââââââââââââââââââ   20.0% 
HTML                     4 repos             âââââââââââââââââââââââââ   11.43% 
Kotlin                   2 repos             âââââââââââââââââââââââââ   5.71% 
C++                      2 repos             âââââââââââââââââââââââââ   5.71%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 29/07/2022 18:54:45 UTC
<!--END_SECTION:waka-->
