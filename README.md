# Friendly-OAuth2-Server
### Starting the authorization server
1. Download java jre 17 version
2. Download Friendly-OAuth2-Server jar file and license.lic file
3. Open the console and enter the command: java -jar ./oauth2-server-test-30.jar
4. Open your browser and enter http://localhost:9000

![Login form](/assets/login-page.png)

5. Login - admin@example.com
6. Password - password1
7. You are in the admin panel

### Server Tuning
- The server supports the following user authorization modes according to the OAuth2 standard
    - OAuth2 code flow
    - OAuth2 implicit flow
    - OAuth2 user password flow
    - OAuth2 client credential flow
    - OAuth2 refresh token flow

- The server supports the following user authorization modes according to the OpenId standard
    - OpenId code flow
    - OpenId implicit flow

- The server supports the following client authorization modes
    - Client secret basic
    - Client secret post
    - Client secret jwt
    - Client key jwt
    - None

> [!WARNING]
> Don't use user authorization mode "OAuth2 client credential flow" and client authorization mode "None".

<!-- ![Login form](/assets/admin-setup-server.png) -->