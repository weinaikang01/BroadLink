# BroadLink
POST https://(OAuthLoginURL)/oauth/v2/token?grant_type=authorization_code&client_id=(client_id)&client_secret=(client_secret)&code=(code) HTTP/1.1
Host: example.com
Accept: application/json, text/javascript
HTTP/1.1 200 OK
Vary: Accept
Content-Type: text/javascript

{
 "access_token": "iM-nK1t_Sw6yyqBk3fAGyw",
 "expires_in": 7200,
 "refresh_token": "cwey5p6RTXa_PuasoLAhSw",
 "token_type": "Bearer"
}
POST https://(OAuthLoginURL)/oauth/v2/token?grant_type=authorization_code&client_id=(client_id)&client_secret=(client_secret)&refresh_token=(refresh_token) HTTP/1.1
Host: example.com
Accept: application/json, text/javascript
HTTP/1.1 200 OK
Vary: Accept
Content-Type: text/javascript

{
 "access_token": "iM-nK1t_Sw6yyqBk3fAGyw",
 "expires_in": 7200,
 "refresh_token": "cwey5p6RTXa_PuasoLAhSw",
 "token_type": "Bearer"
}
HTTP/1.1 200 OK
Vary: Accept
Content-Type: text/javascript

{
 "status" : "0",
 "msg" : "ok",
 "userid" : "xx",
 "loginsession" : "xx",
 "nickname" : "xx"
}
