<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Tab 2-A</ion-title>
        <ion-buttons>
          <ion-back-button default-href="/tabs/tab2" text="Back">Back</ion-back-button>
        </ion-buttons>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 2-A</ion-title>
        </ion-toolbar>
      </ion-header>
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { 
  IonPage, 
  IonHeader, 
  IonToolbar, 
  IonTitle, 
  IonContent,
  IonButtons,
  IonBackButton, 
} from '@ionic/vue';
</script>
