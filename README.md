### jooby
---
https://github.com/jooby-project/jooby

https://jooby.org/

```java
import static org.jooby.Jooby.runApp;

public class App {
  
  public static void main(final String[] args) {
    runApp(args, app -> {
      app.get("/", ctx -> "Welcome to Jooby!");
    });
  }
}

import org.jooby.runApp

fun main(args: Array<String>) {
  runApp(args) {
    get("/") {
      "Welcome to Jooby!"
    }
  }
}
```

```
```

```
```


