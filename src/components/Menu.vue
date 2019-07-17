<template>
  <div>
    <div class="menu-btn">
      <v-btn color="#e95420" class="btn-primary" name="breakfast" onClick={this.handleChange}>Desayuno</v-btn>
      <v-btn color="#e95420" class="btn-primary" name="dinner" onClick={this.handleChange}>Almuerzo/Cena</v-btn>
      <v-btn color="#e95420" class="btn-primary" name="extras" onClick={this.handleChange}>Extras</v-btn>
    </div>
    <div class="container-fluid">
      <div class="row">
        <div class="col-md-7">
          <div class="row">
          </div>
        </div>
        <div class="table">
        <v-flex class="client" md3>
          <v-text-field label="Nombre de Cliente">{name}</v-text-field>
        </v-flex>
        <v-btn color="success" class="btn-success">Enviar a cocina</v-btn>
          <div class="tbl-header">
            <table cellpadding="0" cellspacing="0" border="0">
              <thead>
                <tr>
                  <th>Items</th>
                  <th>Precio</th>
                  <th>Cantidad</th>
                </tr>
              </thead>
            </table>
          </div>
          <div class="tbl-content">
            <table cellpadding="0" cellspacing="0" border="0">
              <tbody>
                <tr>
                  <td>here</td>
                  <td>S/.0.00</td>
                  <td>here</td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Menu'
}
</script>

<style>
  @import '../assets/styles/Menu.css'
</style>
