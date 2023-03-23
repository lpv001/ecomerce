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
    <div class="box">
      
    </div>
  </main>
</template>

<style>
  *{
    padding: 0;
    margin: 0;
    font: inherit;
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
</style>
