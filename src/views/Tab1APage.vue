<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Tab 1-A</ion-title>
        <ion-buttons>
          <ion-back-button default-href="/tabs/tab1" text="Back">Back</ion-back-button>
        </ion-buttons>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 1</ion-title>
        </ion-toolbar>
      </ion-header>
      <h1>Tab 1A Page</h1>
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
} from '@ionic/vue'
</script>
