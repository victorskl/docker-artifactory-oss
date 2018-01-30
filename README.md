# docker-artifactory-oss

Docker compose ready for [JFrog Artifactory OSS](https://jfrog.com/open-source/). Read [more...](https://www.jfrog.com/confluence/display/RTF/Installing+with+Docker)

```
docker-compose --project-name=dev build
docker-compose --project-name=dev up -d

(need to wait awhile on first time bootstrap)
open -a Safari http://localhost:8081
admin:password
```


OSS Limitation

- Only allow package format: Maven, Gradle, Ivy, HELM, SBT, Generic
- https://www.jfrog.com/confluence/display/RTF/Artifactory+Comparison+Matrix