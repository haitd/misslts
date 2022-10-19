# Miss LTS

The idea of this repository is managing source code for both frontend and backend implementation. The structure will be:

```
.
|-- .github/
|   |-- workflows/
|       |-- actions.yml
|-- .gitignore
|-- frontend/
|   |-- build/
|   |-- src/
|   |-- package.json
|   |-- package-lock.json
|-- backend/
|   |-- build/
|   |-- src/
|   |-- package.json
|   |-- package-lock.json
|-- configs/
|   |-- server.cfg
|   |-- rules.cfg
|-- scripts/
|   |-- build.sh
|   |-- deploy.sh
|   |-- validate.sh
|-- README.md
```

Below are some rules for submitting pull request:
- Pull request does not contain temporary file
- Pull request does not contain any binary file
- Pull request does not contain any external node module
- Pull request does not contain any built/output files
- Pull request contains only source code, static assets
