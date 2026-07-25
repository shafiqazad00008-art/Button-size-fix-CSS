# Button-size-fix-CSS
How to fix add to cart button on website
/* Equal size Wishlist & Add To Cart buttons */

.product-form_quantity {
    display: flex;
    align-items: flex-end;
    gap: 15px;
}

.product-form_quantity .st-wishlist-button,
.product-form_quantity .btn-add-to-cart {
    flex: 1 1 0 !important;
    width: 100% !important;
    min-width: 0 !important;
    height: 56px !important;
}
