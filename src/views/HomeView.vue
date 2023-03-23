<template>
  
  <header>
    <div class="even-column">
      <h1>JEANIA SHOP</h1>
      <ul>
        <li>SHOP</li>
        <li>SHOES</li>
        <li>DRESS</li>
      </ul>
    </div>
    <div class="even-column">
      <i>
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
          <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z" />
        </svg>
      </i>
      <i>
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
          <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 3h1.386c.51 0 .955.343 1.087.835l.383 1.437M7.5 14.25a3 3 0 00-3 3h15.75m-12.75-3h11.218c1.121-2.3 2.1-4.684 2.924-7.138a60.114 60.114 0 00-16.536-1.84M7.5 14.25L5.106 5.272M6 20.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm12.75 0a.75.75 0 11-1.5 0 .75.75 0 011.5 0z" />
        </svg>
      </i>
    </div>
  </header>
  <main>
    <section id="banner">
      <h1>HOT SALE IN THIS SUMMER SEASON</h1>
      <p>Offer 50% off to all new customer visiting our SHOP</p>
      <button>START SHOPPING</button>
    </section>
    <section id="ship">
      <h1>Free Shipping For You Till Midnight</h1>
      <i>
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
          <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 3h1.386c.51 0 .955.343 1.087.835l.383 1.437M7.5 14.25a3 3 0 00-3 3h15.75m-12.75-3h11.218c1.121-2.3 2.1-4.684 2.924-7.138a60.114 60.114 0 00-16.536-1.84M7.5 14.25L5.106 5.272M6 20.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm12.75 0a.75.75 0 11-1.5 0 .75.75 0 011.5 0z" />
        </svg>
      </i>
    </section>
    <section id="sm-banner">
      <div class="even-column">
        <p>Platform Velvet Sandals</p>
        <button>Shop Now</button>
      </div>
      <div class="even-column">
        <p>Platform Velvet Sandals</p>
        <button>Shop Now</button>
      </div>
    </section>
  </main>
</template>

<style>
  *{
    padding: 0;
    margin: 0;
    font: inherit;
  }
  body{
    width: 100vw;
    overflow-x: hidden;
  }
  header{
    width: 100%;
    height: 80px;
    background: #000;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
  }
  header .even-column{
    display: flex;
    gap: 20px;
  }
  header .even-column h1{
    font-size: 36px;
    color: #fff;
  }
  header .even-column ul{
    display: flex;
    align-items: center;
    gap: 10px;
  }
  header .even-column ul li{
    color: #fff;
    font-size: 16px;
    list-style: none;
    font-weight: 200;
    border-right: 1px solid silver;
    padding: 0 10px;
  }
  header .even-column ul li:nth-child(3){
    border: none;
  }

  header .even-column i{
    width: 20px;
    height: 20px;
    color: silver;
  }

  #banner{
    width: 100%;
    height: 400px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 0 30px;
    color: #fff;
    background-image: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.4)), url('../assets/images/amazon.jpeg');
  }

  #banner h1{
    font-size: 36px;
    max-width: 30ch;
    margin-bottom: 20px;
  }

  #banner p{
    font-size: 16px;
    margin-bottom: 20px;
  }

  #banner button{
    width: 150px;
    height: 40px;
    border-radius: 20px;
    background: #000;
    color: #fff;
    border: 0;
    box-sizing: content-box;
    padding: 0 20px;
  }
  #ship{
    width: 100%;
    height: 100px;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 10px;
    background: #000;
    width: 100%;
    margin-bottom: 60px;
  }
  #ship h1{
    font-size: 24px;
    color: #fff;
  }
  #ship i{
    width: 25px;
    height: 25px;
    color: #fff;
  }
  #sm-banner{
    padding: 0 100px;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 40px;
  }
  #sm-banner .even-column{
    padding: 40px 20px;
    flex-basis: 100%;
    height: 200px;
    box-sizing: content-box;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-end;
    gap: 20px;
    background-image: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.4)), url('../assets/images/amazon.jpeg');
  }
  #sm-banner .even-column p{
    font-size: 22px;
    max-width: 15ch;
    color: #fff;
  }
  #sm-banner .even-column button{
    width: 120px;
    height: 30px;
    border: none;
    background: #fff;
    color: #000;
    border-radius: 20px;
  }
</style>
