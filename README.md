# dependencies

## gradlew

### environment

local environment

```sh
gradlew clean publish -Pevn=local
# or
gradlew clean publish
```

test environment

```sh
gradlew clean publish -Pevn=test
```

prod environment

```sh
gradlew clean publish -Pevn=prod
```

### maven local build

```sh
gradlew clean publisToMavenLocal
```