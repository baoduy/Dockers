# Service Fabric on MAC

Follow the instruction [here](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-get-started-mac)

1.  Build
    `docker build -t baoduy242/macsfcluster:latest .`

2.  Run
    `docker run --name sftestcluster -d -p 19080:19080 -p 19000:19000 -p 25100-25200:25100-25200 baoduy242/macsfcluster:latest`

3.  Push
    `docker push baoduy242/macsfcluster:latest`
