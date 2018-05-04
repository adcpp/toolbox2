<template>
  <form @submit.prevent="submeterFormulario" class="form">
      <div class="input-control">
          <label for="">Produto</label>
          <input type="text">
      </div>
      <button type="submit">Enviar</button>
  </form>
</template>
