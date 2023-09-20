# KATA_JS_4.4.9
Registration
POST https://blog.kata.academy/api/users
{
	"user": {
			"username": "sergeychudinov",
			"email": "sergeychudinov1986@gmail.com",
			"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY1MGFlYmZhYzMxZGUxMWIwMGJjZDg2MCIsInVzZXJuYW1lIjoic2VyZ2V5Y2h1ZGlub3YiLCJleHAiOjE3MDAzOTg1ODYsImlhdCI6MTY5NTIxNDU4Nn0.MeHLM_y6G6Zv4rwjtn-4oStbovqKumDNpBjZb2g1YMQ"
	}
}

Authentication
POST https://blog.kata.academy/api/users/login
{
	"user": {
			"username": "sergeychudinov",
			"email": "sergeychudinov1986@gmail.com",
			"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY1MGFlYmZhYzMxZGUxMWIwMGJjZDg2MCIsInVzZXJuYW1lIjoic2VyZ2V5Y2h1ZGlub3YiLCJleHAiOjE3MDA0MDA3MDYsImlhdCI6MTY5NTIxNjcwNn0.Ql7GcKCdiNwMhqplCe3v_y_MNjUxc8cCiRKN4Nbwy9g"
	}
}

Get Current User
GET https://blog.kata.academy/api/user
Authorization Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY1MGFlYmZhYzMxZGUxMWIwMGJjZDg2MCIsInVzZXJuYW1lIjoic2VyZ2V5Y2h1ZGlub3YiLCJleHAiOjE3MDA0MDA3MDYsImlhdCI6MTY5NTIxNjcwNn0.Ql7GcKCdiNwMhqplCe3v_y_MNjUxc8cCiRKN4Nbwy9g
{
	"user": {
			"username": "sergeychudinov",
			"email": "sergeychudinov1986@gmail.com",
			"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY1MGFlYmZhYzMxZGUxMWIwMGJjZDg2MCIsInVzZXJuYW1lIjoic2VyZ2V5Y2h1ZGlub3YiLCJleHAiOjE3MDA0MDEzMjEsImlhdCI6MTY5NTIxNzMyMX0.551BJ2wi0z450QT-WGEXQPUroCL3tOc8nd8fqujS4zI"
	}
}