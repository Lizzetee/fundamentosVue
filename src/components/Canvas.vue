<template>
    <div class="text-center mt-5">
      <!-- Spinner centrado -->
      
  
      <!-- Botón con espacio debajo del spinner -->
      <div class="mb-4">
        <button
          class="btn btn-primary"
          type="button"
          data-bs-toggle="offcanvas"
          data-bs-target="#offcanvasBottom"
          aria-controls="offcanvasBottom"
        >
          MÁS INFORMACIÓN
        </button>
      </div>
    </div>
  
    <!-- Offcanvas que aparece desde abajo -->
    <div
      class="offcanvas offcanvas-bottom"
      tabindex="-1"
      id="offcanvasBottom"
      aria-labelledby="offcanvasBottomLabel"
    >
      <div class="offcanvas-header">
        <h5 class="offcanvas-title" id="offcanvasBottomLabel">BIENVENIDO A XPEDITEC</h5>
        <button
          type="button"
          class="btn-close"
          data-bs-dismiss="offcanvas"
          aria-label="Close"
        ></button>
      </div>
      <div class="offcanvas-body text-center">
        <p>
          Regístrate para tener toda tu documentación en orden acerca de tu residencia.
          Aquí recibirás todas las notificaciones del proceso que debes realizar.
          ¡Mantente al tanto y no te pierdas de toda la información!
        </p>
      </div>
    </div>
  </template>
  