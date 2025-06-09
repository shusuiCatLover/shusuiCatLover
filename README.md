<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=5cc0cd&height=120&section=header"/>

  <img src="assets/heading.svg" alt="shusui-logo"/>
  
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&pause=1000&color=5cc0cd&center=true&vcenter=true&random=false&width=940&lines=%20%20%20%20%20Fullstack+Developer;%20%20%20%20%20Deep+in+Studies;%20%20%20%20%20Fluent+in+English+and+Portuguese" alt="Typing SVG"/>
</div>

```go
package main

import "fmt"

type Competences struct {
	Primary         []string
	Secondary       []string
	SecretTechnique string
}

type Shusui struct {
	CharacterClass  string
	Title           string
	CurrentStudying string
	CurrentMissions []string
	Competences     Competences
}

func main() {
	shusui := Shusui{
		CharacterClass:  "Fullstack",
		Title:           "Innovator",
		CurrentStudying: "DevOps",
		CurrentMissions: []string{
			"Doing Art Commissions",
			"Coding Modern Webpages",
			"Learning about web protocols",
		},
		Competences: Competences{
			Primary:         []string{"Python", "Lua", "Java", "Golang"},
			Secondary:       []string{"HTML", "CSS", "TS", "Kotlin"},
			SecretTechnique: "No mouse required for this Neovim user",
		},
	}

	fmt.Printf("Shusui's Character Info:\n")
	fmt.Printf("Class: %s\n", shusui.CharacterClass)
	fmt.Printf("Title: %s\n", shusui.Title)
	fmt.Printf("Currently studying: %s\n", shusui.CurrentStudying)
	fmt.Println("Current missions:")
	for _, mission := range shusui.CurrentMissions {
		fmt.Printf("- %s\n", mission)
	}
	fmt.Println("Competences:")
	fmt.Println("  Primary skills:", shusui.Competences.Primary)
	fmt.Println("  Secondary skills:", shusui.Competences.Secondary)
	fmt.Printf("  Secret Technique: %s\n", shusui.Competences.SecretTechnique)
}
```

<div align="center">
  <img width="52%" src="https://github-readme-stats.vercel.app/api?username=shusuiCatLover&show_icons=true&count_private=true&title_color=5cc0cd&icon_color=ea4094&text_color=C9D1D9&bg_color=0D1117&hide_border=true" alt="Shusui GitHub Stats"/>
  <img width="39%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shusuiCatLover&layout=compact&title_color=5cc0cd&text_color=C9D1D9&bg_color=0D1117&hide_border=true"/>
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=shusuiCatLover&theme=redical&hide_border=true&area=true" alt="Contribution Graph"/>
</div>

> *"Trying to make a good difference"*

### Tech Stack
<div align="center" style="display: flex; flex-wrap: wrap; justify-content: center; gap: 15px;">
  <img src="https://skillicons.dev/icons?i=linux,bash,neovim,go,lua,python,typescript,react,angular,tailwind,html,css&theme=dark" alt="Tech Stack"/>
</div>

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=5cc0cd&height=120&section=footer"/>
</div>
