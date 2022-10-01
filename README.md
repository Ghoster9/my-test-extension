# How its work

### First make build
`docker build ahmadzky08/my-test-extension .`

### Push to hub if you need
`docker push ahmadzky08/my-test-extension`

### Install extension in local docker desktop
`docker extension install ahmadzky08/my-test-extension`

### And go to docker desktop

Click Call backend and you can see `{"Message":"Hello world"}`

### If there is a change then:

build again:

`docker build -t ahmadzky08/my-test-extension`

and update:

`docker extension update ahmadzky08/my-test-extension`

And you can look at docker desktop in the extensions.

or

`docker extension ls`

Refrence

[Docker](https://www.docker.com/blog/build-your-first-docker-extension/?utm_campaign=2022-05-19-brnd-extensionhowtoblog&utm_medium=blog&utm_source=linkedin) Build Your First Docker Extension