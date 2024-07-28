```mermaid
erDiagram
    tb_user {
        INT id
        VARCHAR name
        VARCHAR role
    }
    tb_products {
        INT id
        VARCHAR name
        VARCHAR description
        FLOAT price
    }
    tb_cart {
        INT id
    }
    tb_product_cart {
        INT id
        INT cart_id
        INT product_id
    }
    tb_user_cart {
        INT id
        INT cart_id
        INT user_id
    }
```