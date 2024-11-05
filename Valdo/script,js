// Função de zoom ao passar mouse
document.querySelectorAll('.product-img').forEach(item => {
    item.addEventListener('mouseover', () => {
        item.style.transform = 'scale(1.2)';
    });
    item.addEventListener('mouseout', () => {
        item.style.transform = 'scale(1)';
    });
});

// Carrossel de produtos - Simulação simples
let carouselIndex = 0;
const products = document.querySelectorAll('.product-item');
function showProduct(index) {
    products.forEach((product, i) => {
        product.style.display = i === index ? 'block' : 'none';
    });
}
showProduct(carouselIndex);
