<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Tab 1</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 1</ion-title>
        </ion-toolbar>
      </ion-header>
      <h1>Tab 1</h1>
      <p><router-link to="/tabs/tab1/tab1a">Go to tab 1a</router-link></p>
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
} from '@ionic/vue'
</script>
