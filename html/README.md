
    git clone https://github.com/jpaas-lib/jpaas-app-demos

    cd html/
    appname="my-html-demo" # change to your own name

    jpaas push ${appname} -i 1 -m 64M -b https://github.com/cloudfoundry-community/nginx-buildpack.git
    curl ${appname}.jpaas-edu.baidu.com

