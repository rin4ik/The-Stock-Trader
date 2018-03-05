<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
<router-link class="navbar-brand"  to='/'>Stock Trader</router-link>
  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <router-link to="/portfolio" class="nav-item" tag="li" active-class="active"><a class="nav-link">Portfolio</a></router-link>
      <router-link to="/stocks" tag="li" class="nav-item" active-class="active"><a class="nav-link">Stocks</a></router-link>
   </ul>
   <ul class="nav navbar-nav navbar-right">
      <li class="nav-item"><a class="nav-link" href="#">End Day</a></li>
      
       <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Save & Load
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
        <li>
          <a class="dropdown-item" href="#">Save Data</a>
        </li>  
        <li> 
                  <a class="dropdown-item" href="#">Load Data</a>
 
        </li>
 
        </div>
      </li>
   </ul>
  </div>
</nav>
</template>
