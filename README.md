<div align="center">
  <img
    src="assets/banner.png"
    alt="Ramindu Abeygunawardane GitHub Banner"
    width="100%"
  />
</div>

<br />

<div align="center">

# Hi, I'm Ramindu Abeygunawardane

### Software Engineer · Backend & Distributed Systems · Data & AI Engineering

<p>
  Computer Science & Engineering graduate focused on building reliable,
  scalable and data-intensive software systems.
</p>

<p>
  <a href="https://www.linkedin.com/in/Ramindu-Abeygunawardane" title="LinkedIn">
    <img
      src="https://skillicons.dev/icons?i=linkedin&theme=dark"
      alt="LinkedIn"
      width="46"
    />
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/RaminduA" title="GitHub">
    <img
      src="https://skillicons.dev/icons?i=github&theme=dark"
      alt="GitHub"
      width="46"
    />
  </a>
  &nbsp;&nbsp;
  <a href="mailto:raminduanjana@gmail.com" title="Email">
    <img
      src="https://skillicons.dev/icons?i=gmail&theme=dark"
      alt="Gmail"
      width="46"
    />
  </a>
  &nbsp;&nbsp;
  <a href="https://x.com/RaminduAbey" title="X">
    <img
      src="https://skillicons.dev/icons?i=twitter&theme=dark"
      alt="X"
      width="46"
    />
  </a>
</p>

</div>

## About Me

```go
package main

import "fmt"

type Experience struct {
	Role    string
	Company string
	Current bool
}

type Engineer struct {
	Name           string
	Major          string
	Education      string
	Specialization string
	Experience     []Experience
	Location       string
}

func (e Engineer) Introduce() {
	fmt.Printf("Hi, I'm %s.\n", e.Name)
	fmt.Printf("I'm based in %s.\n", e.Location)
	fmt.Printf(
		"I studied %s at the %s, specializing in %s.\n",
		e.Major,
		e.Education,
		e.Specialization,
	)

	fmt.Println("Experience:")
	for _, experience := range e.Experience {
		status := "Previously"

		if experience.Current {
			status = "Currently"
		}

		fmt.Printf(
			"  - %s: %s at %s\n",
			status,
			experience.Role,
			experience.Company,
		)
	}
}

func main() {
	ramindu := Engineer{
		Name:           "Ramindu Abeygunawardane",
		Major:          "Computer Science & Engineering",
		Education:      "University of Moratuwa",
		Specialization: "Data Science & Engineering",
		Experience: []Experience{
			{
				Role:    "Associate AI Engineer",
				Company: "DeepAI Labs",
				Current: false,
			},
			{
				Role:    "Software Engineering Intern",
				Company: "ZeroBeta",
				Current: false,
			},
		},
		Location: "Galle, Sri Lanka",
	}

	ramindu.Introduce()
}
```

## Areas of Interest

<div align="center">

<img src="https://img.shields.io/badge/Backend%20Engineering-111827?style=for-the-badge" alt="Backend Engineering" />
<img src="https://img.shields.io/badge/Distributed%20Systems-111827?style=for-the-badge" alt="Distributed Systems" />
<img src="https://img.shields.io/badge/Data%20Engineering-111827?style=for-the-badge" alt="Data Engineering" />

<br />

<img src="https://img.shields.io/badge/Machine%20Learning-111827?style=for-the-badge" alt="Machine Learning" />
<img src="https://img.shields.io/badge/Cloud%20Infrastructure-111827?style=for-the-badge" alt="Cloud Infrastructure" />
<img src="https://img.shields.io/badge/MLOps-111827?style=for-the-badge" alt="MLOps" />

</div>

---

## Technology Stack

### Languages and Scripting

[![Languages and Scripting](https://skillicons.dev/icons?i=java,py,go,js,ts,bash,cs,cpp,dart,kotlin,latex,md,php\&theme=dark)](https://skillicons.dev)

### Backend Development

[![Backend Development](https://skillicons.dev/icons?i=spring,django,fastapi,flask,express,nodejs,bun,graphql,hibernate,maven,npm,dotnet,laravel\&theme=dark)](https://skillicons.dev)

### Frontend Development

[![Frontend Development](https://skillicons.dev/icons?i=nextjs,react,html,css,bootstrap,jquery,materialui,tailwind,vite,threejs\&theme=dark)](https://skillicons.dev)

### Application Development

[![Application Development](https://skillicons.dev/icons?i=androidstudio,flutter,dart,electron,qt\&theme=dark)](https://skillicons.dev)

### UI Design and Prototyping

[![Design and Prototyping](https://skillicons.dev/icons?i=figma,codepen\&theme=dark)](https://skillicons.dev)

### Database Systems

[![Database Systems](https://skillicons.dev/icons?i=postgres,mysql,sqlite,redis,mongodb,dynamodb,firebase,supabase\&theme=dark)](https://skillicons.dev)

### Machine Learning and Data Streaming

[![Machine Learning and Data Streaming](https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv,kafka,pkl\&theme=dark)](https://skillicons.dev)

### Cloud Platforms

[![Cloud Platforms](https://skillicons.dev/icons?i=aws,gcp\&theme=dark)](https://skillicons.dev)

### Infrastructure

[![Infrastructure](https://skillicons.dev/icons?i=docker,terraform,nginx,cloudflare\&theme=dark)](https://skillicons.dev)

### CI/CD and Deployment

[![CI/CD and Deployment](https://skillicons.dev/icons?i=githubactions,vercel,heroku,netlify\&theme=dark)](https://skillicons.dev)

### Source Control and Collaboration

[![Source Control and Collaboration](https://skillicons.dev/icons?i=git,github,gitlab,bitbucket,notion\&theme=dark)](https://skillicons.dev)

### API Development

[![API Development](https://skillicons.dev/icons?i=postman\&theme=dark)](https://skillicons.dev)

### IDEs and Code Editors

[![IDEs and Code Editors](https://skillicons.dev/icons?i=idea,pycharm,webstorm,vscode,visualstudio,clion,phpstorm,eclipse,atom\&theme=dark)](https://skillicons.dev)

### Operating Systems

[![Operating Systems](https://skillicons.dev/icons?i=linux,windows\&theme=dark)](https://skillicons.dev)

---

## GitHub Statistics

<p align="center">
  <img
    src="https://github-readme-streak-stats.herokuapp.com/?user=RaminduA&theme=github-dark-blue&hide_border=true"
    alt="Ramindu's GitHub Contribution Streak"
  />
</p>


## Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/Ramindu-Abeygunawardane" title="LinkedIn">
    <img src="https://skillicons.dev/icons?i=linkedin&theme=dark" alt="LinkedIn" width="52" />
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/RaminduA" title="GitHub">
    <img src="https://skillicons.dev/icons?i=github&theme=dark" alt="GitHub" width="52" />
  </a>
  &nbsp;&nbsp;
  <a href="mailto:raminduanjana@gmail.com" title="Gmail">
    <img src="https://skillicons.dev/icons?i=gmail&theme=dark" alt="Gmail" width="52" />
  </a>
  &nbsp;&nbsp;
  <a href="https://x.com/RaminduAbey" title="X">
    <img src="https://skillicons.dev/icons?i=twitter&theme=dark" alt="X" width="52" />
  </a>
</p>



<p align="center">
  <i>
    Open to opportunities in backend development, data engineering and applied AI.
  </i>
</p>

<p align="center">
  <sub>Last updated: 22 July 2026</sub>
</p>
