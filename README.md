# Interprocess-Communications-in-Distributed-Environment

Implementation of Java Sockets to show RPC communication between a server and clients.


## Running through the Intelliji IDE

Go to `Run | Edit Configurations` for both the `ClientApplication.java` and `ServerApplication.java`. Under 
VM options add the following:

```
--module-path $PATH_TO_FX --add-modules javafx.controls,javafx.fxml --add-opens javafx.controls/com.sun.javafx.scene.control.behavior=ALL-UNNAMED --add-opens javafx.controls/com.sun.javafx.scene.control=ALL-UNNAMED --add-opens javafx.base/com.sun.javafx.binding=ALL-UNNAMED --add-opens javafx.base/com.sun.javafx.event=ALL-UNNAMED --add-opens javafx.graphics/com.sun.javafx.stage=ALL-UNNAMED
```

> __Note:__ Replace $PATH_TO_FX with the full path to the javafx-sdk `lib` folder
