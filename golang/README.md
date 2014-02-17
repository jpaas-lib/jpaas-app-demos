
    git clone https://github.com/jpaas-lib/jpaas-app-demos

    cd golang/
    appname="my-go-demo" # change to your own name

    gcf push ${appname} -i 1 -m 64M -b https://github.com/michaljemala/cloudfoundry-buildpack-go.git
    curl ${appname}.cfapps.io

