<template>
  <div class="wallet-not-found">
    <div class="wrap">
      <div class="page-container">

        <div class="content-block">
          <div class="block-title">Oops! Wallet not found :(</div>
          <div class="buttons">

            <router-link to="/create-wallet">
              <div class="get-a-free-wallet mid__round-button__blue-filled__blue-border">{{$t('common.getAFreeWallet')}}</div>
            </router-link>
            <router-link to="/access-my-wallet">
              <div class="access-my-wallet mid-round-button-green-filled-green-border">{{$t('common.accessMyWallet')}}</div>
            </router-link>

          </div>
          <div class="spaceman">
            <img src="~@/assets/images/home/spaceman.png">
          </div>
        </div>

      </div>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {}
  }
}
</script>

<style lang="scss" scoped>
@import "WalletNotFoundContainer.scss";
</style>
