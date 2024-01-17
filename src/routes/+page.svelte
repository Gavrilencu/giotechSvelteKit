<script>
    // Script-ul poate include logica suplimentară dacă este necesar
</script>

<div class="container">
    <div class="text-section">
        <h1 class="title">GMM BIOTECHNOLOGY</h1>
        <p class="description">
            GMM Biotechnology este formată dintr-o echipă de oameni dedicați,
            care muncesc cu drag pentru a oferi cele mai bune soluții pentru
            diagnostice de laborator. Oferim spitalelor și laboratoarelor din R.
            Moldova o gamă variată de servicii, furnizând teste PCR, reactive,
            echipament și consumabile de cea mai înaltă calitate.
        </p>
    </div>
    <div
        class="image-section"
        style="background-image: url('/path/to/lab-image.jpg');"
    >
        <!-- Imaginea laboratorului ar putea fi aici ca fundal, adresa URL trebuie înlocuită cu calea corectă -->
    </div>
</div>

<style>
    .container {
        display: flex;
        align-items: center;
        justify-content: space-between;
        margin: 0;
        padding: 2rem;
        background-color: #2d2d7f; /* Presupunând că acesta este culoarea de fundal */
    }

    .text-section {
        flex-basis: 50%;
        color: white;
    }

    .title {
        font-size: 2.5rem;
        margin-bottom: 1rem;
    }

    .description {
        font-size: 1rem;
        line-height: 1.6;
    }

    .image-section {
        flex-basis: 50%;
        height: 300px; /* Ajustează în funcție de dimensiunea dorită */
        background-size: cover;
        background-position: center;
        border-radius: 1rem; /* Adaugă un border-radius dacă este necesar */
    }

    /* Media queries pentru responsivitate */
    @media (max-width: 768px) {
        .container {
            flex-direction: column;
        }

        .image-section {
            width: 100%; /* Ajustează lățimea pentru ecranele mici */
            margin-top: 1rem;
        }
    }
</style>
