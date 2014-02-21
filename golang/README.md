
    git clone https://github.com/jpaas-lib/jpaas-app-demos

    cd golang/
    appname="my-go-demo" # change to your own name

    jpaas push ${appname} -i 1 -m 64M -b https://github.com/jpaas-lib/jpaas-buildpack-golang
    curl ${appname}.jpaas-edu.baidu.com

