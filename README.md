<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=4e85d3&height=120&section=header"/>

  <img src="assets/heading.svg" alt="shusui-logo"/>
  
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&pause=1000&color=4e85d3&center=true&vcenter=true&random=false&width=940&lines=%20%20%20%20%20Software+Developer;%20%20%20%20%20Data+Science;%20%20%20%20%20System+Analysis;%20%20%20%20%20Linux+Fanatic" alt="Typing SVG"/>
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

### Tech Stack
<div align="center" style="display: flex; flex-wrap: wrap; justify-content: center; gap: 15px;">
  <img src="https://skillicons.dev/icons?i=linux,bash,neovim,go,lua,python,typescript,react,angular,tailwind,html,css&theme=dark" alt="Tech Stack"/>
</div>

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=4e85d3&height=120&section=footer"/>
</div>
