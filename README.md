# dependencies

## gradlew

### environment

local environment

```sh
gradlew clean publish -Pprofile=local
# or
gradlew clean publish
```

test environment

```sh
gradlew clean publish -Pprofile=test
```

prod environment

```sh
gradlew clean publish -Pprofile=prod
```

### maven local build

```sh
gradlew clean publisToMavenLocal
```
