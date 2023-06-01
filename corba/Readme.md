# IDL CORBA

ASSIGNMENT 2

## Files :

-   ReverseClient.java
-   ReverseImpl.java
-   ReverseModule.idl
-   ReverseServer.java

## Terminal 1

```
idlj -fall ReverseModule.idl
```

```
javac *.java ReverseModule/*.java
```

```
orbd -ORBInitialPort 1050&
```

```
java ReverseServer -ORBInitialPort 1050& -ORBInitialHost localhost&
```

## Terminal 2

```
java ReverseClient -ORBInitialPort 1050 -ORBInitialHost localhost
```
