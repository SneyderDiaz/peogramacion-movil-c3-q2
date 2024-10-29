# Componentes de Ionic con Vue

A continuación, se presentan 10 componentes comunes de Ionic que se pueden utilizar en aplicaciones Vue, junto con ejemplos de código.

## 1. IonHeader
```vue
<IonHeader>
  <IonToolbar>
    <IonTitle>Mi Aplicación</IonTitle>
  </IonToolbar>
</IonHeader>

# componente tolbar

<IonToolbar>
  <IonTitle>Encabezado</IonTitle>
</IonToolbar>

# componente title

<IonHeader>
  <IonToolbar>
    <IonTitle>Título de la Página</IonTitle>
  </IonToolbar>
</IonHeader>

#componente button

<IonButton expand="full">Presionar Aquí</IonButton>

# Componente Card

<IonCard>
  <IonCardHeader>
    <IonCardTitle>Título de la Tarjeta</IonCardTitle>
  </IonCardHeader>
  <IonCardContent>
    Este es el contenido de la tarjeta.
  </IonCardContent>
</IonCard>

# Componente Lista

<IonList>
  <IonItem>
    Elemento 1
  </IonItem>
  <IonItem>
    Elemento 2
  </IonItem>
</IonList>

#Componente Item

<IonList>
  <IonItem button>
    <IonLabel>Opción 1</IonLabel>
  </IonItem>
</IonList>

# Componente Iput

<IonItem>
  <IonLabel position="floating">Ingrese su nombre</IonLabel>
  <IonInput></IonInput>
</IonItem>

# Componente Select 

<IonItem>
  <IonLabel>Seleccione una opción</IonLabel>
  <IonSelect>
    <IonSelectOption value="opcion1">Opción 1</IonSelectOption>
    <IonSelectOption value="opcion2">Opción 2</IonSelectOption>
  </IonSelect>
</IonItem>

#Componente Alerta

<IonAlert
  isOpen={showAlert}
  onDidDismiss={() => setShowAlert(false)}
  header={'Alerta'}
  message={'¿Está seguro de que desea continuar?'}
  buttons={['Cancelar', 'Aceptar']}
/>







