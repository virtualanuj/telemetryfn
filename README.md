# telemetryfn
Telemetry function as a service

## Quick start
## Pre-requisites
Docker 17.10.0-ce or later installed and running
A Docker Hub account (Docker Hub) (or other Docker-compliant registry)
Log Docker into your Docker Hub account: docker login

### 1. Homebrew - MacOS
If you're on a Mac and use Homebrew, this one is for you:

brew install fn

### 2. Run Fn Server
Now fire up an Fn server:

fn start

### 3. Clone Repo from Github
Gitrepo: https://github.com/virtualanuj/telemetryfn.git

### 4. Run your function locally
fn run

## 5. Test

### ab -n 5000 -c 15 'http://localhost:8080/r/info/info -d '{"name":"Go World"}''
