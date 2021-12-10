# MV-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Marlon Véliz

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'mv-product-card'; 

<ProductCard
    product={ product }
    initialValues={{
        count: 6,
        maxCount: 10,
    }}
>
    {
        ({ reset, increaseBy, count, isMaxCountReached, maxCount }) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>
        )
    }
</ProductCard>
```