[![Blog](https://img.shields.io/badge/Blog-0?style=flat-square&logo=gatsby&color=181717&logoColor=white)](https://micnncim.com)
[![Twitter](https://img.shields.io/badge/Twitter-0?style=flat-square&logo=twitter&color=1DA1F2&logoColor=white)](https://twitter.com/micnncim)
[![Speaker Deck](https://img.shields.io/badge/Speaker_Deck-0?style=flat-square&logo=speaker-deck&color=009287&logoColor=white)](https://speakerdeck.com/micnncim)

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=micnncim&show_icons=true&count_private=true" />
</p>

#### 🍎 Recent Projects
{{range recentRepos 5}}
- [{{.Name}}]({{.URL}}){{if ne (len .Description) 0}} - {{.Description}}{{end}}
{{- end}}

#### 🌱 Recent Contributions
{{range recentContributions 5}}
- [{{.Repo.Name}}]({{.Repo.URL}}) ({{humanize .OccurredAt}}){{if ne (len .Repo.Description) 0}} - {{.Repo.Description}}{{end}}
{{- end}}

#### 👪  Recent Followers
{{range followers 5}}
- [{{.Login}}]({{.URL}})
{{- end}}
