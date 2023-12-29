# GP-Product-Card

Este es un paquete de pruebas de despliegue en NPM


### Juan Grimaldo

## Ejemplo
```
import { ProductCard, ProductButtons, ProductImage, ProductTitle } from 'gp-product-card';
```

```
<ProductCard
  key={product.id}
  product={product}
  initialValues={{
    count: 4,
    // maxCount: 10
  }}
>

  {
    ({ reset, isMaxCountReached, increaseBy, count, maxCount }) => (
      <>
        <ProductImage />
        <ProductTitle />
        <ProductButtons />
      </>
    )
  }
</ProductCard>
```