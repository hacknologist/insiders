<h1 align="center">UrbanDictionary</h1>

```mermaid
graph LR
COMPANY_NAME{UrbanDictionary}
COMPANY_NAME ---> U{Users} ---> UN[2]
COMPANY_NAME ---> R{Repositories} ---> RN[3]
COMPANY_NAME ---> G{Gists} ---> GN[1]
COMPANY_NAME ---> ML{Most Used<br>Languages}
ML --> TeX[TeX]
ML --> JavaScript[JavaScript]
ML --> C++[C++]
```