<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Login</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 1</ion-title>
        </ion-toolbar>
      </ion-header>

  <ion-card>
    <ion-card-header>
      <ion-card-title>Login</ion-card-title>
    </ion-card-header>
    <!-- Input with placeholder -->
    <ion-input type="text" placeholder="Input Your Username"></ion-input>
    <ion-input type="password" placeholder="Input Your Password"></ion-input>
    <ion-button color="light">Register</ion-button>
    <ion-button color="dark">Login</ion-button>
    
  </ion-card>
      <ExploreContainer name="Tab 1 page" />
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
// import ExploreContainer from '@/components/ExploreContainer.vue';
import { IonButton } from '@ionic/vue';
import { defineComponent } from 'vue';

export default  {
  name: 'Tab1',
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage, IonButton }
}
</script>