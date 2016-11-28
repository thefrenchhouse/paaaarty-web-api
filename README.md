# Paaaaty public web API


## Endpoints

### Party
- **POST** `/api/v1/party/:id/add_guest`
  - userId

- **POST** `/api/v1/party/:id/generate`
  - Genre
  - Timeline

- **POST** `/api/v1/party/`
  - ownerId
  - name

### User

- **POST** `/api/v1/user/`
  - displayName
  - accessToken
  - refreshToken
  - spotifyProfileId