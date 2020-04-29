<template>
  <div id="App">
    <div class="App__top-bar">
      <div class="App__top-bar-bell">yo</div>
      <div class="App__top-bar-location">Moscow</div>
      <div class="App__top-bar-avatar">(:)</div>
    </div>
    <div class="App__search">
      <div class="App__search-logo">Yandex</div>
      <div class="App__search-arrow">
        <div class="App__search-arrow-scan">(o)</div>
      </div>
    </div>
    <div class="App__services">
      <div class="App__services-service-item">
        <div class="App__services-service-item-logo"></div>
        <div class="App__services-service-item-text">text</div>
      </div> 
      <div class="App__services-service-item">
        <div class="App__services-service-item-logo"></div>
        <div class="App__services-service-item-text">text</div>
      </div>    
      <div class="App__services-service-item">
        <div class="App__services-service-item-logo"></div>
        <div class="App__services-service-item-text">text</div>
      </div>    
      <div class="App__services-service-item">
        <div class="App__services-service-item-logo"></div>
        <div class="App__services-service-item-text">text</div>
      </div>    
      <div class="App__services-service-item">
        <div class="App__services-service-item-logo"></div>
        <div class="App__services-service-item-text">text</div>
      </div>    
    </div>
    <div class="App__informer-cards">
      <div class="App__informer-cards-card"></div>
      <div class="App__informer-cards-card"></div>
    </div>
  </div>
</template>

<script>

</script>

<style lang="scss">
.App {
  background-color: #efefef;

  &__search-logo {
    margin-top: 32px;
    margin-bottom: 24px;
    font-size: 40px;
    width: 100%;
    text-align: center;
  }

  &__search-arrow {
    width: 100%;
    height: 40px;
    border: 1px solid #c4c4c4;
    border-radius: 4px;

  }

  &__top-bar {
    display: flex;
    justify-content: space-between;
    margin-top: 24px;
  }

    &__top-bar-bell {
      background-color: pink;
      background-color: black;
    }

  &__services {
    margin-top: 20px;
    display: flex;
    width: 100%;
  }
    &__services-service-item {
        margin-right: 16px;
    }

      &__services-service-item-logo {
        width: 48px;
        height: 48px;
        border-color: #efefef;
        border-radius: 12px;
        background-color: gray;
      }
      &__services-service-item-text {
        width: 100%;
        text-align: center;
        margin-top: 8px;
      }
  &__informer-cards {
    background-color: white;
    display: inline-flex;
    overflow: hidden;
    margin-top: 24px;
    padding-left: 8px;
  }
    &__informer-cards-card {
      width: 200px;
      height: 80px;
      background-color: #c4c4c4;
      border-radius: 12px;
      margin-right: 16px

    }
}


</style>
