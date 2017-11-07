<template>
  <div>
    <RootHeader />
    <div class="container">
      <div class="row">
        <RootSidebar />
        <div class="col-lg-9">
          <RootBanners />
          <div class="row">
            <RootProducts />
          </div>
        </div>
      </div>
    </div>
  <RootFooter />
  </div>
</template>

<script>
import RootHeader from './components/root/header'
import RootSidebar from './components/root/sidebar'
import RootProducts from './components/root/products'
import RootBanners from './components/root/banners'
import RootFooter from './components/root/footer'
export default {
  name: 'app',
  components: {
    RootHeader,
    RootSidebar,
    RootProducts,
    RootBanners,
    RootFooter
  }
}
</script>

<style src="./assets/sass/app.scss" lang="sass"></style>