# helm-wrapper
Bash wrapper script for Helm

## Usage
Add the script to your location in your path e.g.:
```
cp helm /usr/local/bin/helm
chmod +x /usr/local/bin/helm
```

### set helm version to use
Set helm version using an env var:
```
export HELM_VERSION=2.6.1
```

Set helm version for the current directory:
```
echo "2.6.1" > .helm_version
```

### install helm version
```
helm install-version 2.6.1
```

### list installed helm versions
```
helm versions
```
