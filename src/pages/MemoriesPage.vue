<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title> All Memories</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content>
      <ion-list>
        <ion-item>Max </ion-item>
        <ion-item>Max </ion-item>
        <ion-item>Max </ion-item>
      </ion-list>
    </ion-content>
  </ion-page>
</template>

<script>
import {
  IonPage,
  IonToolbar,
  IonHeader,
  IonTitle,
  IonContent,
  IonList,
  IonItem,
} from "@ionic/vue";
export default {
  components: {
    IonPage,
    IonHeader,
    IonTitle,
    IonContent,
    IonToolbar,
    IonList,
    IonItem,
  },
};
</script>
