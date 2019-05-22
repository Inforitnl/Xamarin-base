[![logo](./logo.jpg)](https://inforit.nl)

# Xamarin

Our Xamarin base image

# Instructions:

1. update dockerfile
2. build local version:

   ```
   docker build -t inforitnl/imagename .
   ```

3. push new version to dockerhub:

   ```
   docker push inforitnl/imagename:latest
   ```

4. tag and push again (optional but recommended):

   ```
   docker tag inforitnl/imagename inforitnl/imagename:1
   docker push inforitnl/imagename:1
   ```

# Usage

```
FROM inforitnl/base


```
