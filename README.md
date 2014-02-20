jpaas-app-demos
===============

### Step 1. Download jpaas CLI

	MacOS 64：
	Linux 64：
	Linux 32：
	Win 64：
	Win 32：

### Step 2. Login

	$ jpaas login \
		-a <API endpoint> \
		-u <User Name> \
		-p <Access Token> \
		-o <Your Org Name> \
		-s <Your Space Name>

### Step 3. Hello World!

	git clone https://github.com/jpaas-lib/jpaas-app-demos

	cd <Demo App>
	appname="my-demo" # change to your own name

	jpaas push ${appname} -i 1 -m 64M -b <Buildpack Url>
	curl ${appname}.<API endpoint>
