## Chrome Web Store API workflow

The workflow use [`chrome-webstore-upload`](https://github.com/fregante/chrome-webstore-upload).

Get `CLIENT_ID` and `CLIENT_SECRET` from the [Google Console](https://console.developers.google.com/apis/credentials).

Get the `REFRESH_TOKEN` with [chrome-webstore-upload-keys](https://github.com/fregante/chrome-webstore-upload-keys).

> Refresh Token can expired, to renew it execute the following command and update the environment variable.

```bash
npx chrome-webstore-upload-keys
```
