<script>
export default {
  data() {
    return { 
     
    }
  }
}
</script>

<template>
  <header>
    <div>
      <img src="../assets/img/dc-logo.png" alt="Logo">
    </div>
    <ul>
      <li>
        <a href="#"> Character </a>
      </li>
      <li> 
        <a href="#"> Comics </a>
      </li>
      <li> 
        <a href="#"> Movies </a>
      </li>
      <li> 
        <a href="#"> Tv </a>
      </li>
      <li> 
        <a href="#"> Games </a>
      </li>
      <li>
        <a href="#"> Videos </a>
      </li>
      <li>
        <a href="#"> Fans </a>
      </li>
      <li>
        <a href="#"> News </a>
      </li>
      <li>
        <a href="#"> Shop </a>
      </li>
    </ul>
  </header>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

header {
  display: flex;
  justify-content: space-around;
  align-items: center;
  text-align: center;
  padding: 20px;

    div {
      img{
        width: 80px;
      }
    }
  ul {
    list-style: none;
    display: flex;

    li {
      text-transform: uppercase;
      font-weight: bolder;
      font-size: smaller;
      color: $mainGrey;
      padding: 20px;
      margin-right: 5px;

      :hover {
      color: $mainGrey;
      opacity: 0.5;
      cursor: pointer;
      }

      a {
        color: $mainGrey;
        text-decoration: none;
      }
      :active {
        color: $mainColor;
      }
    }
  }
}

h1 {
  color: $mainColor;
}
</style>
