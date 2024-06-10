-{
	"image": "mcr.microsoft.com/devcontainers/go:1.22",
	"features": {
		"ghcr.io/devcontainers/features/sshd:1": {}
	},
	"remoteUser": "vscode",
	"customizations": {
		"vscode": {
			"extensions": [
				"golang.go"
			],
			"settings": {
				"go.toolsManagement.checkForUpdates": "local",
				"go.useLanguageServer": true,
				"go.gopath": "/go"
			}
		}
	},
	"runArgs": [
		"--cap-add=SYS_PTRACE",
		"--security-opt",
		"seccomp=unconfined"
	]
}
👋 Hi, I’m @954681
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
954681/954681 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
