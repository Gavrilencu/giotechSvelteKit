<script>
    export let product;
    export let onClose;
</script>

<div class="modal-background" on:click={onClose}>
    <div class="modal-content" on:click|stopPropagation>
        <h2>{product.name}</h2>
        <p>Categorie: {product.category}</p>
        <p>Descriere: {product.description}</p>
        {#if product.image}
            <img
                src={`http://localhost:3000/${product.image}`}
                alt={product.name}
            />
        {/if}
    </div>
</div>

<style>
    .modal-background {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-color: rgba(0, 0, 0, 0.5);
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .modal-content {
        background: white;
        padding: 20px;
        border-radius: 8px;
        max-width: 500px;
        text-align: center;
    }
    img {
        max-width: 100%;
        height: auto;
        margin-top: 10px;
    }
</style>
