# android-instapago
Librería para Android que se conecta con API de Instapago

Llave pública:
461fe598147e4f1a955eab0e810a42a7

ID
3A2AFC58-C037-45DE-9B65-CBEA5284EB5C

To upload your library to bintray, learn from [here](https://medium.com/@ryanseys/publishing-to-maven-central-and-jcenter-2b6376424856#.3518citej) how to get the data to fill the following environment variables

```bash
export BINTRAY_USER="<something>"
export BINTRAY_API_KEY="<something>"

export MAVEN_USER_TOKEN="<something>"
export MAVEN_USER_PASS="<something>"
```
Add this to your `~/.bashrc` or `.zshrc`


# Uploading
Run the following to build and upload everything:

> ./gradlew bintrayUpload

# Finishing up
Sign in to https://bintray.com/ to see how you did. If this is your first deploy of the package then you’ll have to send a message to get approved for that package name. A message should pop up on the site explaining how to go about sending that request. Approval for this should take less than a couple hours.
