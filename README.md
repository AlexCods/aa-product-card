
```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from "aa-product-card";
```


```
<ProductCard
  product={product}
  initialValues={{
    count: 4,
    maxCount: 10,
  }}
>
  {({ reset, count, increaseBy, isMaxCountReached }) => (
    <>
      <ProductImage />
      <ProductTitle />
      <ProductButtons />
    </>
  )}
</ProductCard>
```
