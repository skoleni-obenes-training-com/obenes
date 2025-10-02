# obenes devops
- build go:
  - `CGO_ENABLED=0 go build -o /server /src/server.go`
  - [reference](https://docs.docker.com/build/building/multi-stage/)

- ci/cd reference
  - [job rules](https://docs.gitlab.com/ci/jobs/job_rules/)
  - [predefined vars](https://docs.gitlab.com/ci/variables/predefined_variables/)