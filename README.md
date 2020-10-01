## Expo Release Management

### Setup

```sh
git checkout develop
yarn install
```

### Development

```sh
REACT_NATIVE_API_DOMAIN=192.168.x.x:5000 yarn install
```

### Deployment

Set up CircleCI env vars

- EXPO_USERNAME
- EXPO_PASSWORD
- REACT_NATIVE_DEV_API_DOMAIN
- REACT_NATIVE_STAGING_API_DOMAIN
