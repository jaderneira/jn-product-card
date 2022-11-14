

## Example

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'jn-product-card'
```

```
  <ProductCard
    product={ product }            
    initialValues={{
      count: 4,
      maxCount: 10
    }}
  >
    {
      ( {reset, increaseBy, isMaxCountReached, maxCount, count } ) => (
        <>                
          <ProductCard.Image />
          <ProductCard.Title />
          <ProductCard.Buttons />                  
        </>
      )
    }
  </ProductCard>
```