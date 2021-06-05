# Products API

API desenvolvida em Node.JS/Express com BD NoSQL Firestore.

Para manipular o modelo de produto com os seguintes atributos:
        id
        productName
        productDescription
        productPrice

O consumo da API se dá via protocolo http:

router.post('/product', addProduct);
router.get('/products', getAllProducts);
router.get('/product/:id', getProduct);
router.put('/product/:id', updateProduct);
router.delete('/product/:id', deleteProduct);

Futuras implementações:
  - Adição de foto do produto.
  - Controle de segurança via JWT.
  - Deploy para produção.
