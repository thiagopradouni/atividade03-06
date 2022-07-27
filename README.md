# atividade03-06

<ion-content [fullscreen]="true">
  <div id="posicionamento">
    <ion-grid>
      <ion-row>
        <ion-col size="9">
          <ion-item>
            <ion-input placeholder="Nome de um produto"></ion-input>
          </ion-item>
        </ion-col>
        <ion-col size="3">
          <ion-button color="primary" size="small" >
            <ion-icon name="save-outline"></ion-icon>
          </ion-button>
        </ion-col>
      </ion-row>
      <ion-row>
        <ion-col size="9">
          <ion-item>
            {{variavel_lista}}
          </ion-item>
        </ion-col>
        <ion-col size="3">
          <ion-button color="danger" size="small" >
            <ion-icon name="trash-outline"></ion-icon>
          </ion-button>
        </ion-col>
      </ion-row>
    </ion-grid>
