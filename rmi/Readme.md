# RMI

ASSIGNMENT 1

## Files :

-   AddClient.java
-   AddServer.java
-   AddServerImpl.java
-   AddServerIntf.java

## Terminal 1

```
javac *.java
```

```
rmic AddServerImpl
```

## Create Client And Server Folder

### Client Folder:

-   AddClient.class
-   AddServerImpl_Stub.class
-   AddServerIntf.class

### Server Folder:

-   AddServer.class
-   AddServerImpl_Stub.class
-   AddServerImpl.class
-   AddServerIntf.class

```
rmiregistry
```

## Terminal 2

```
java AddServer
```

## Terminal 3

```
java AddClient 127.0.0.1 8 9
```
