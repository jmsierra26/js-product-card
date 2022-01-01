# JS-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Jesús Sierra

## Ejemplo

```
import { ProductButtons, ProductCard, ProductImage, ProductTitle } from 'js-product-card';
```

```
const product = {
  id: '1',
  title: 'Coffee Mug - Card',
  // img: './coffee-mug.png',
}
```

```
<ProductCard
  product={product}
  initialValues={{
    count: 4,
    maxCount: 10,
  }}
>
  {({ reset, increaseBy, isMaxCountReached, count }) => (
    <>
      <ProductImage />
      <ProductTitle />
      <ProductButtons />
    </>
  )}
</ProductCard>
```
