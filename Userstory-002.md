# Userstory-004

Another code block

```js
export default ({ products }) => {
    return products.map(product => {
        return (
            <div className="product" key={product.id}>
                <div className="p-name">{product.name}</div>
                <div className="p-desc">{product.description}</div>
            </div>
        );
    });
};
```

Just add "```"js and close it.