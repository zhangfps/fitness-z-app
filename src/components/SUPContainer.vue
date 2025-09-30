<template>
  <ion-card>
    <ion-card-header>
      <ion-card-title>Nothing here... </ion-card-title>
      <!-- <ion-card-subtitle>What? Why?</ion-card-subtitle> -->
    </ion-card-header>

    <ion-card-content>
      You must be signed in to view this content.
    </ion-card-content>
    <ion-button aria-label="Help" shape="round">
      <ion-icon
        aria-hidden="true"
        slot="icon-only"
        :icon="helpCircle"
      ></ion-icon>
    </ion-button>
  </ion-card>
</template>

<script setup lang="ts">
import {
  IonCard,
  IonCardContent,
  IonCardHeader,
  IonCardSubtitle,
  IonCardTitle,
  IonPopover,
  IonButton,
} from "@ionic/vue";
import { helpCircle } from "ionicons/icons";
</script>

<style scoped>
ion-card {
  --background: #000;
  --color: #9efff0;
}

ion-card-title {
  --color: #52ffe4;
}

ion-card-subtitle {
  --color: #d1fff8;
}
</style>
