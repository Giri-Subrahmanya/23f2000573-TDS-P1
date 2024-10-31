* The users data was scraped using request library. The returned request was converted to json. The request made for fetching users was : `https://api.github.com/users/{i['login']}/repos?page={x}&per_page=100` and the request made for fetching their corresponding repositories was `    repo.extend(r.get(f"https://api.github.com/users/{i['login']}/repos?page={x}&per_page=100",headers=headers).json())
`
* 
* To come up with a good analysis, it is very much recommended to write a clean code. One should be convenient with the analytical frameworks like panadas, numpy, sklearn command line environment. 
