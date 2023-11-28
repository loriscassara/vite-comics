<!-- 
	START SCRIPT
-->

<script>
	export default {
		name: 'AppMain',
		data(){
			return {

			}
		}
	}
</script>

<!-- 
	START TEMPLATE	
-->

<template>
    <!-- main elements -->

    <main>
        <div class="main-top-container">
            <div class="top-container">
                contenuto
            </div>
        </div>
        <div class="main-bottom-container">
            <div class="bottom-container">
                <div class="digital-comics">
                    <img src="../assets/image/buy-comics-digital-comics.png" alt="digital-comics">
                    <p>DIGITAL COMICS</p>
                </div>
                <div class="dc-merchandise">
                    <img src="../assets/image/buy-comics-merchandise.png" alt="dc-merchandise">
                    <p>DC MERCHANDISE</p>
                </div>
                <div class="subscription">
                    <img src="../assets/image/buy-comics-subscriptions.png" alt="subscription">
                    <p>SUBSCRIPTION</p>
                </div>
                <div class="comic-shop-locator">
                    <img src="../assets/image/buy-comics-shop-locator.png" alt="comic-shop-locator">
                    <p>COMIC SHOP LOCATOR</p>
                </div>
                <div class="dc-power-visa">
                    <img src="../assets/image/buy-dc-power-visa.svg" alt="dc-power-visa">
                    <p>DC POWER VISA</p>
                </div>
            </div>
        </div>
    </main>
</template>

<!-- 
	START STYLE
-->

<style scoped>
/* common UI elements */

.main-top-container { background-color: #1c1c1c; }

.main-bottom-container { background-color: #0282f9; }

/* main elements */

.top-container {
    width: 80%;
    margin: 0 auto;
    height: 10rem;
    color: white;
}

.bottom-container {
    width: 80%;
    margin: 0 auto;
    height: 10rem;
    color: white;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.digital-comics, .dc-merchandise, .subscription, .comic-shop-locator, .dc-power-visa {
    display: flex;
    align-items: center;
    transition: all .55s ease;
}

.bottom-container img {
    width: 5rem;
    padding: 1rem;
}

.comic-shop-locator img { width: 4rem; }

.bottom-container p { font-size: smaller; }

.digital-comics:hover, .dc-merchandise:hover, .subscription:hover, .comic-shop-locator:hover, .dc-power-visa:hover {
    cursor: pointer;
    transform: scale(1.2);
}
</style>