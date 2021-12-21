# nodemongosignupverification

Before running in production also make sure that you update the secret property in the config.json file, it is used to sign and verify JWT tokens for authentication, change it to a random string to ensure nobody else can generate a JWT with the same secret and gain unauthorized access to your api. A quick and easy way is join a couple of GUIDs together to make a long random string (e.g. from https://www.guidgenerator.com/).
