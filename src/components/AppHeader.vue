<template>
  <header>
    <div class="nav-container">
        <img src="../assets/img/dc-logo.png" alt="DC logo">
        <ul class="nav-header">
           <li>Characters</li>
           <li>Comics</li>
           <li>Movies</li>
           <li>Tv</li>
           <li>Games</li>
           <li>Collectibles</li>
           <li>videos</li>
           <li>Fans</li>
           <li>News</li>
           <li>Shop</li>
        </ul>
    </div>
  </header>
</template>

<script>
export default {

}
</script>

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    div.nav-container {
        width: 100vw;
        height: 100px;
        display: flex;
        justify-content: space-around;
        align-items: center;
        background-color: #FFFFFF;
    }

    div.nav-container img {
        height: 70px;
        width: 70px;
    }

    div.nav-container ul.nav-header {
        list-style: none;
        color: black;
        display: flex;
        flex-direction: row;
        align-items: center;
    }

    div.nav-container ul.nav-header li {
        padding-right: 1rem;
        text-transform: uppercase;
    }

</style>