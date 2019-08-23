### jolt
---
https://github.com/bazaarvoice/jolt

```java
// jolt-core/src/test/java/com/bazaarvoice/jolt/chainr/transforms

public class TransformTestResult {
  
  public final Object input;
  public final Object spec;
  
  TransformTestResult( Object input, Object spec ) {
    this.input = input;
    this.spec = spec;
  }
}


Chainr chainr = JsonUtils.classpathToLit( "/path/to/chainr/spec.json" );
Object input = elsaticSearchHit.getSource();
Object output = chainr.transform( input );
return output;
```

```sh
mvn covertura:cobertura
open jolt-core/target/site/cobertura/index.html
```

```
```
