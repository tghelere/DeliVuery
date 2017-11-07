<template>
   <div class="col-lg-4 col-md-6 mb-4">
        <div class="card h-100">
            <a href="#"><img class="card-img-top" src="http://placehold.it/700x400" alt=""></a>
            <div class="card-body">
                <h4 class="card-title">
                <a href="#">Item 1</a>
                </h4>
                <p class="card-text">Aqui exibe a descrição do produto</p> 
                <div class="row">
                    <div class="col-md-8 mb-8">               
                        <h5 class="price">R$ 24,99</h5>
                    </div>
                    <div class="col-md-4 mb-4">
                        <i class="fa fa-cart-plus fa-3x cart" aria-hidden="true"></i>
                    </div>
                </div>
            </div>
            <div class="card-footer">
                <small class="text-muted">&#9733; &#9733; &#9733; &#9733; &#9734;</small>
            </div>
        </div>
    </div>
    
</template>

<script>
    export default {}
</script>
<style>
.price{
    background: #1f7a1f;
    color: #ebfaeb;
    line-height: 40px;
    text-align:center;
    border: 1px solid #33cc33;
    font-weight: bold;
}
i.cart{
    line-height: 40px;
}
</style>
