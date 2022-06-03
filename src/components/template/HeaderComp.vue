<template>
<header>
    <div class="menu-esquerdo">
      <span> <Routerlink to="/">Home</Routerlink>  </span>
      <span>|</span>
      <span><Routerlink to="/Jogadores">Jogadores</Routerlink>  </span> 
      <span>|</span>
      <span><Routerlink to="/Times">Times</Routerlink>  </span>
    </div>
    <div class="menu-direito">
      <span>Sair</span>
    </div>
  </header>
</template>

<style>
 header {
 background-color: rgb(red, green, blue);
 height: 15%;
 font-size: 1.3rem;
 padding-left: 2rem;
 color: white;
 display: flex;
 align-items: center;
 justify-content: space-between;
}

header span {
    padding: 0 20px;
}
  
</style>