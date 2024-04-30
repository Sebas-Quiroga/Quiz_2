<template>
  <ion-page>
    <ion-tabs>
      <ion-router-outlet></ion-router-outlet>
      <ion-tab-bar slot="bottom">
        <ion-tab-button tab="CLIENTE" href="/tabs/CLIENTE">
          <ion-icon aria-hidden="true" :icon="triangle" />
          <ion-label>CLIENTE</ion-label>
        </ion-tab-button>

        <ion-tab-button tab="EMPLEADO" href="/tabs/EMPLEADO">
          <ion-icon aria-hidden="true" :icon="ellipse" />
          <ion-label>EMPLEADO</ion-label>
        </ion-tab-button>

        <ion-tab-button tab="ESTUDIANTE" href="/tabs/ESTUDIANTE">
          <ion-icon aria-hidden="true" :icon="square" />
          <ion-label>ESTUDIANTE</ion-label>
        </ion-tab-button>
      </ion-tab-bar>
    </ion-tabs>
  </ion-page>
</template>

<script setup lang="ts">
import { IonTabBar, IonTabButton, IonTabs, IonLabel, IonIcon, IonPage, IonRouterOutlet } from '@ionic/vue';
import { ellipse, square, triangle } from 'ionicons/icons';
</script>
