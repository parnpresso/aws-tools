# aws-tools

```
docker build -t aws-tools:latest .
docker run --rm -it -v /Users/parnpresso/workspace/odds/quit-smoking/backoffice:/app -v /var/run/docker.sock:/var/run/docker.sock aws-tools:latest bash

aws configure
eval $(aws ecr get-login --no-include-email --region ap-northeast-1) 2> /dev/null


```
