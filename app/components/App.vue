<template>
    <Page>
        <ActionBar title="Welcome to WebViewExt Confirm Test"/>
        <GridLayout columns="*" rows="*">
            <WebViewExt src="~/assets/hello.html" col="0" row="0"/>
        </GridLayout>
    </Page>
</template>

<script >
  export default {
    data() {
      return {
        msg: 'Hello World!'
      }
    }
  }
</script>

<style scoped>
    ActionBar {
        background-color: #53ba82;
        color: #ffffff;
    }

    .message {
        vertical-align: center;
        text-align: center;
        font-size: 20;
        color: #333333;
    }
</style>
